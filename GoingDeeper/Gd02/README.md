# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 서승환
- 리뷰어 : 김민혁


# PRT(Peer Review Template)
- [X]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
        - 중요! 해당 조건을 만족하는 부분을 캡쳐해 근거로 첨부
     
    ![image](https://github.com/user-attachments/assets/46a98a90-4ded-4d20-a7b6-8d345579c1ed)
    ![image](https://github.com/user-attachments/assets/79f3b792-2e75-47d5-9c09-72d558e26368)
    ![image](https://github.com/user-attachments/assets/19549e30-2237-4b38-bed5-fac57144c6e0)
    ![image](https://github.com/user-attachments/assets/912109e9-3a05-4e0d-b3fc-271cdf937090)
    ![image](https://github.com/user-attachments/assets/3344811e-af07-4419-a886-c1afab53deda)

    > num_words, vocab_size를 달리해 accuracy와 f1-score(weight)을 잘 도출하였고 정리하신 것이 인상깊었습니다. 보팅 방식도 깔끔하게 코딩하셔서 결과를 확인하시는게 좋았어요.

    
- [X]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭을 왜 핵심적이라고 생각하는지 확인
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 기술했는지 확인
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
     
    ![image](https://github.com/user-attachments/assets/9eba2b77-3bff-41ac-ac14-d8a89257a95a)
    ![image](https://github.com/user-attachments/assets/9ee75dee-3819-4cfa-a19c-c0996ed07064)

    > 아무래도 Tf-IDF 방식으로 단어를 벡터화 하는 부분이 가장 핵심이였고, 데이터가 불균형인 데이터에 Weighted Avg F1-Score가 왜 중요하고 평가 하겠다는지 그 의도가 잘 드러났고, 보팅하는 방식에서도 선정한 모델로 개별 분류기를 정의한 부분도 좋았습니다.
        
- [X]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 프로젝트 평가 기준에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부

    ![image](https://github.com/user-attachments/assets/6f48fd35-37a1-4ea8-8b30-06cbb22a2e23)

    > 딥러닝 모델과 비교하는 부분에서 validation set를 구성하고 희소 행렬인지 확인해본 결과 데이터가 잘 바뀌지 않아서 밀집 행렬로 바꿔보는 시도로 진행한 사항이 인상 깊었습니다. 
        
- [X]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
     
    ![image](https://github.com/user-attachments/assets/89659095-fb1b-425e-9b68-cb5285bf6b56)

    > Vocab size에 대해 정의하시고 시도해본 경험이 잘 드러났고요, 또한 벡터화와 임베딩 레이어가 얼마나 중요한지 느낄 수 있었습니다.
        
- [X]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화/모듈화했는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부

    ![image](https://github.com/user-attachments/assets/c982e1e1-702e-436a-89b6-73f91d5a1ea3)

    > define된 부분은 없었지만, gru 모델을 사용할 때 모델 구성과 학습이 깔끔하게 진행되었습니다. 후에 예측값을 통한 f1 score weighted avg 값을 뽑아 정리한 것이 좋았습니다.

# 회고(참고 링크 및 코드 개선)
```
같은 프로젝트 주제이지만 저랑 다른 시도를 통해 여러 인사이트를 얻는 것이 좋았습니다.
특히 희소 행렬을 밀집 행렬로 바꾸는 부분에서 다른 디테일이 엿보였어요.
또한, 학습 시간이 오래걸렸을 텐데, 많은 num_words, 8가지 모델을 모두 학습하고 표로 시각화해줘서 깔끔하게 정리가 되었습니다.
앞으로도 열심히 하는 승환님 응원하겠습니다!
```

