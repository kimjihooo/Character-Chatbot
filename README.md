
# 드라마 캐릭터 챗봇
- 목적 : <응답하라 1988>의 네명의 캐릭터(정환, 택, 동룡, 선우)를 페르소나로 챗봇을 구현합니다. 연애 시뮬레이션 게임의 형태로 사용자가 네명의 캐릭터와 채팅을 나누고 자신에게 맞는 최종 인물을 선택하는 것이 목적입니다.
- 일정 : 2022.09 - 2022.01


## 주요 내용
### 1. 데이터 증강
2019년 EMNLP 에서 발표된 EDA: Easy Data Augmentation Techniques for Boosting Performance on Text Classification Tasks 논문 참고해 다음과 같은 방법으로 데이터 증강

(1) 문장 내 임의의 두 단어의 위치를 바꿈(Random Swap)

(2) 문장의 위치를 바꿈

(3) 임의의 단어를 삭제(Random Deletion)

(4) 코사인 유사도가 높은 문장 대체

### 2. 모델
유사도 기반의 챗봇과 KoGPT2 기반의 챗봇을 구현하고 성능이 더 좋은 **KoGPT2** 선택

### 3. 결과
<img width="710" alt="정환택" src="https://user-images.githubusercontent.com/97178674/212591131-fe181eed-6256-47a9-81d6-1b6388a1a2e5.png">

