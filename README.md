# Project_Architecture
Carefree Story's Project Architecture

# 운동 보조 Application

- 운동 보조 애플리케이션
    - `[User Data / Gym Data]` 자신만의 루틴 설정 및 공유
        - 즐겨찾기 통해 자신의 루틴 Setting 후 운동 시작
            - `Gym Data 에는 일단 3대 운동 [Bench Press, Squat, Dead Lift] 만 넣어주셔도 좋을 것 같습니다.`
        - 빅 데이터 / Authorize 된 트레이너 등에 기반한 추천 루틴 제공
        - 팝업창 느낌으로 컨디션 기입
    - 나의 운동 기록
        - 운동 횟수, 중량 등 운동 정보를 저장
        - 운동 별 중량 변화를 그래프로 보여주기
        - Inbody 기록, 변화 그래프
    - Challenge
        - 팀 또는 다른 단체에서 주최하는 챌린지(예를 들어, 몇 키로 마라톤 같은)
    - 웨이트 트레이닝 카테고리 생성 (대근육 / 소근육 / 코어 / 유산소)
        - 각 운동 방법 및 정보 제공
        - (Set / Reps / Pause) Counting 제공
        - 웨이트 트레이닝 카테고리 내 사용자 데이터 분석 후 프로필 데이터와 연동