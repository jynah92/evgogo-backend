# 고속도로 휴게소 전기차 충전기 정보 어플리케이션 (Backend)
## 1. 배경
- 이미 많은 사람들이 사용하고 있는 어플들 (EV Infra, 충전국밥 등)이 존재
- 하지만 고속도로 운전 중에 확인하려고 하는 경우 멈춰설 수 없음
- 따라서, 최대한 적은 클릭 수로 원하는 정보를 볼 수 있는 어플리케이션 필요
## 2. 기능
- 충전기 정보 한 번에 표시
    - 현재 충전 중인지 대기 중인지
    - 충전 중이라면 몇 분째 충전 중인지
    - 현재 차량이 충전할 수 있는 충전기인지
- 가려는 방향 (상행, 하행)을 인식하여 몇 키로 남았는지
    - 현재 위치 정보 사용
    - 움직임 또는 사용자 설정을 통해 확인
- 지도 표시
    - 현재 위치 및 충전기 위치 표시
- 네비게이션 앱 연동
    - TMAP, 카카오내비 등
## 3. REST API (작성 예정)
## 4. 외부 데이터 및 API
### < 고속도로 공공데이터 포털 >
- 도로중심선 (이정, XY 좌표)
### < 공공데이터 포털 >
- 전기자동차 충전소 정보 (한국전력공사)
- 전기차 충전소 운영 정보 (한국환경공단)
## 5. 사용 기술
- Java, Spring Boot, Spring Batch, JPA