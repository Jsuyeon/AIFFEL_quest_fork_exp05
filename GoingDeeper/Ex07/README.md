# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 정민규.
- 리뷰어 : 정수연.


# PRT(Peer Review Template)
- [x]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
        - 중요! 해당 조건을 만족하는 부분을 캡쳐해 근거로 첨부
        - 아래 추가적인 실험 내용에서 더 자세하게 캡처를 완료하였습니다
        - 중요한 부분은 masking 에 비율에따른 정확도의 차이를 확인하는 부분이 BERT 성능 향상 문제를 해결하는데 도움을 준 것을 확인할 수 있었습니다
        - <img width="560" height="293" alt="image" src="https://github.com/user-attachments/assets/3ec5655c-e97f-4fa2-bf1a-182ff361fbef" />

    
- [x]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭을 왜 핵심적이라고 생각하는지 확인
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 기술했는지 확인
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - BERT 의 가장 중요한 부분인 MASKING , 문장 PARI 생성하는 부분이 핵심 부분이라고 생각했습니다
        -<img width="528" height="545" alt="image" src="https://github.com/user-attachments/assets/68552cfd-6c4c-4828-bd35-9f11de87eccb" />
        - <img width="541" height="524" alt="image" src="https://github.com/user-attachments/assets/c53a22b0-cc8e-4a89-8f9a-b3060a719a41" />


- [x]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 프로젝트 평가 기준에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - 
        - masking 비율에 따른 정확도가 어떻게 변화하는지 추가로 실험 수행하신 걸 확인할 수 있었습니다
        - 0.15/0.25/0.35 로 살펴보았을 때 비율이 증가할 수 록 정확도에 좀 더 좋은 영향을 미쳤습니다 
        - <img width="530" height="202" alt="image" src="https://github.com/user-attachments/assets/59fddb8d-b9b0-4311-b68f-8e3ec93b0ff8" />
        - <img width="532" height="203" alt="image" src="https://github.com/user-attachments/assets/b0db243f-6222-4e2e-9118-c40e9bd23210" />
        - <img width="533" height="200" alt="image" src="https://github.com/user-attachments/assets/ac16754a-81d0-487f-b80e-404815d79654" />

        - <img width="530" height="332" alt="image" src="https://github.com/user-attachments/assets/9ae5477d-bd17-4b8c-a855-5e45c62f02e2" />

        
- [x]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - 전체적인 코드 수행 내용을 확인할 수 있었습니다
        - <img width="535" height="298" alt="image" src="https://github.com/user-attachments/assets/8375095b-350f-4bb5-adb3-8519966c8772" />

        
- [x]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화/모듈화했는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - 코드의 전체적인 진행 사항이 잘 알 수 있게 깔끔하게 코드가 작성되어있습니다
        -<img width="535" height="489" alt="image" src="https://github.com/user-attachments/assets/b1502cd7-d2a3-4592-8b78-1fcb18f5ab0b" />


# 회고(참고 링크 및 코드 개선)
궁금한 부분을 추가적으로 실험한 부분이 새로운 Insight를 얻을 수 있었습니다. masking 비율을 다양하게 시도하며 좋은 정확도를 내는 비율을 찾아봐야겠다고 생각했습니다
