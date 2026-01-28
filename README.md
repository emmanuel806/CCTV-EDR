# CCTV-EDR: CCTV-based Emergency Detection & Response System (CCTV 인프라를 활용한 비상 상황 탐지 및 신고 시스템)

CCTV-EDR은 CCTV 영상을 기반으로 객체 탐지 AI 모델을 활용하여 사람이 쓰러지거나 실신하는 상황을 자동으로 탐지합니다. 또한, 지연 시간을 최소화하기 위해서 응급 상황에 실시간으로 대처할 수 있는 신고 시스템을 개발하였습니다. 그리고, 응급 상황이 포착된 CCTV 영상을 실시간으로 모니터링 할 수 있습니다.

## Rewards
### 수상
- **대회명**: 2021 WINNER LINC+ 캡스톤디자인 언택트 경진대회
- **기간**: 2021.09 - 2021.12
- **주최**: 교육부, LINC
- **수상**: **2등상**
### SW 저작권
- **제 C-2021-057286 호**

## Tech Stacks
- YOLOv5
- NodeJS
- Nginx
- MongoDB
- Docker

## Features
- 실시간 객체 탐지
- 실시간 서버 알림
- WebSocket을 활용한 실시간 모니터링

## Architectur
<img src="C:\Users\rlaxo\OneDrive\HOME\PROJECT\CCTV-EDR\assets\process.png" alt="process" width="800">  
<img src="C:\Users\rlaxo\OneDrive\HOME\PROJECT\CCTV-EDR\assets\architecture.png" alt="architecture" width="800">

## **Demo** 

## **Future** 
1. 데이터 처리를 위한 서버 및 데이터베이스 견고화
2. 객체 탐지 모델 개선