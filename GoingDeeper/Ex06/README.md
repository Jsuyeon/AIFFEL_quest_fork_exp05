# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 정민규.
- 리뷰어 : 정수연.


# PRT(Peer Review Template)
- [x]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
        - 중요! 해당 조건을 만족하는 부분을 캡쳐해 근거로 첨부
        - 
        - data augmentation 을 수행하신 후에 모델의 loss 가 어떻게 변화하는지 그림으로 첨부하신 걸 확인했습니다
        - 또한 생성한 결과를 attention map 으로 그린후에 정량/정성적으로 평가한 결과를 볼 수 있었습니다
        - <img width="329" height="167" alt="image" src="https://github.com/user-attachments/assets/400fc958-7f62-418b-90ef-006c881baf19" />
        - <img width="510" height="168" alt="image" src="https://github.com/user-attachments/assets/4394d02b-20b9-4555-8c30-106f5c510371" />
        - <img width="509" height="487" alt="image" src="https://github.com/user-attachments/assets/f5d5f681-ff4a-4248-9479-6776a1b17b7f" />
        - <img width="509" height="497" alt="image" src="https://github.com/user-attachments/assets/ee84e246-6b1c-472f-b9cd-c93c07a5fa75" />


    
- [x]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭을 왜 핵심적이라고 생각하는지 확인
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 기술했는지 확인
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
     
        - 가장 핵심이라고 생각하는 건 attention map을 그리는 것이 transformer를 공부한 핵심이라고 생각합니다
        - <img width="510" height="401" alt="image" src="https://github.com/user-attachments/assets/6473f98b-aa95-4a56-8b60-d57bfa942a1e" />

        - <img width="470" height="435" alt="image" src="https://github.com/user-attachments/assets/64cf6e33-68d7-46da-8003-5f26cbdaf867" />

        
- [x]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 프로젝트 평가 기준에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - 
        - 실험을 따로 정리를 하고 결과로 보여주신 부분을 확인 할 수 있었습니다
        - <img width="330" height="158" alt="image" src="https://github.com/user-attachments/assets/a94c183b-3dcc-499a-ba88-cd054639f4fc" />

        
- [x]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - 
        - 과정 전체적인 부분을 잘 정리해주신 것 같습니다
        - <img width="530" height="158" alt="image" src="https://github.com/user-attachments/assets/e21092b7-eb04-4b9f-9c50-2224c76fa887" />

        
- [x]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화/모듈화했는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - 
        - 결과를 보기 쉽게 잘 정리해서 print해서 보고 있다고 생각합니다
        - 그리고 함수 input 이 어떤 것이 들어가는지 항상 정리를 잘 하신다고 생각했습니다
        - <img width="506" height="388" alt="image" src="https://github.com/user-attachments/assets/3b7f54a0-80ce-4c67-a612-3ebf9bb8f49e" />



# 회고(참고 링크 및 코드 개선)
- 항상 코드 정리를 깔끔하게 하시고 실험을 깔끔하게 하려고 정리하려고 하시는 것 같은게 느껴져서 배울 점이 많은 코드인 것 같습니다
