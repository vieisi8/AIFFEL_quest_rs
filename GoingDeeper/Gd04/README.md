# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 서승환
- 리뷰어 : 진수민

# PRT(Peer Review Template)
- [O]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
        - 중요! 해당 조건을 만족하는 부분을 캡쳐해 근거로 첨부
        - 데이터 전처리 진행
        - ![image](https://github.com/user-attachments/assets/a5e2e1d8-73e3-431b-9349-7c4d234aebce)
        - 데이터셋에 맞는 모델 사용
        - ![image](https://github.com/user-attachments/assets/634a080e-e3a0-4ca7-bbf3-fe157ff66b72)
        - Loss 값이 감소하는 추세 확인
        - ![image](https://github.com/user-attachments/assets/3113e74d-26e0-4b97-baf7-0e0fe82ec44f)

  
- [O]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭을 왜 핵심적이라고 생각하는지 확인
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 기술했는지 확인
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - 데이터 프레임화 하여 이해를 도움
        -![image](https://github.com/user-attachments/assets/a7dd6036-2e18-423c-aed3-5ce041b972ec)
        - epoch별로 결과를 출력하여 학습 진행도를 사람이 이해 할 수 있도록 함
        - ![image](https://github.com/user-attachments/assets/50b578db-2bb3-46d0-8e20-ba0804d07dee)


        
- [O]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 프로젝트 평가 기준에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - 토큰화 진행 및 pandas로 output을 하여 눈으로 확인 가능하게 함
        - ![image](https://github.com/user-attachments/assets/0bd6e18e-349e-4328-a706-4cf3caf75e27)

        
- [O]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - ![image](https://github.com/user-attachments/assets/2fe16d76-e353-42b3-94e7-f460670babc7)

        
- [O]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화/모듈화했는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부


# 회고(참고 링크 및 코드 개선)
```
- 프로젝트에 어떻게 하면 데이터셋을 더 잘 이해할 수 있는가? 가 담겨있어서 좋습니다.
- 제 프로젝트와 비교하여, 전처리도 더 진행하셨는데 loss 값 차이가 있던 게 batch 사이즈 등 하이퍼파라미터가 조금씩 달라서 일 것 같다는 생각이 듭니다.
- 훈련 epoch 별로 번역값 예시를 확인 할 수 있게 해서 어느정도 학습된지 직관적으로 처리한 부분이 인상깊습니다. 
```

