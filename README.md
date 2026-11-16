# 김서연 | 소프트웨어 개발

부산대학교에서 컴퓨터공학을 전공하며 Android 앱과 웹 서비스의 화면과 사용자 흐름을 개발해 왔습니다.

[포트폴리오](https://syeoniism.github.io/portfolio/) · [이메일](mailto:seoyeon5442@pusan.ac.kr) · [블로그](https://blog.naver.com/padoobaq)

## 주요 프로젝트

### [BOOKUS](https://github.com/syeoniism/BOOKUS_android)

독서 인증과 회차별 책 교환을 지원하는 2인 Android 앱 프로젝트입니다.

- Kotlin과 XML로 홈·그룹·책 교환·일정 화면을 구현했습니다. 모임장 권한 판별 방식을 통일해 화면마다 권한 상태가 달라지는 문제를 해결했습니다.
- 약 540장의 이미지로 MobileNetV2 기반 책 분류 모델을 개발하고, TensorFlow Lite로 변환해 Android 앱에 연동했습니다.
- 별도 테스트 이미지 112장에서 **정확도 92.86%, 정밀도 95.45%**를 기록했습니다.

### [유리 베기 (Glass Slash)](https://github.com/syeoniism/glass-slash) · 2026.11

유리를 비슷한 면적의 두 조각으로 나눌수록 높은 점수를 얻는 2D 브라우저 게임입니다.

- JavaScript로 볼록 다각형 절단과 면적 계산을 구현하고, 두 조각의 면적 비율을 점수로 환산했습니다. Matter.js로 강체 물리를 처리하고 보로노이 다이어그램으로 파편을 생성했습니다.
- 모바일 터치 조작과 절단·파편 생성 과정을 시각화하는 모드를 구현했습니다. [웹에서 플레이](https://syeoniism.github.io/glass-slash/)

### [Career Balance](https://github.com/syeoniism/career-balance)

이력서·자기소개서 작성과 커뮤니티를 한곳에서 이용할 수 있는 2인 웹 프로젝트입니다.

- 서비스의 주요 화면과 프론트엔드를 설계하고, 취업 관련 주제에 투표한 뒤 선택지별 결과를 확인하고 댓글을 남기는 흐름을 구현했습니다.

### [TECH WEEK Physical AI](https://github.com/syeoniism/PNU-TECHWEEK-260930) · 2026.09

Webots에서 TurtleBot3가 사전 지도와 GPS 없이 LiDAR와 카메라로 실내를 탐색하고, 목표물에 접근한 뒤 출발점으로 복귀하는 미션을 시뮬레이션한 해커톤 프로젝트입니다.

## 프로젝트에 사용한 기술

- **Android** · Kotlin, XML, Firebase Firestore
- **웹** · HTML, CSS, JavaScript, Node.js, Express, MySQL
- **머신러닝** · Python, TensorFlow, TensorFlow Lite
