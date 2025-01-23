# 📂 Projects as a Back-end Engineer
## 🍔 [Auction Cook](https://github.com/SyingSHY/AuctionCook-BE)
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
<img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=Spring%20Boot&logoColor=white"/>
![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonwebservices&logoColor=white)  
**2024년 1학기 (프로젝트 완료)**   
: 팀 프로젝트(**Server 1**, Client 2, Design 1) - Media Software Engineering (아주대학교 디지털미디어학과)  
: 요리 재료를 실시간 경매로 획득하여 요리를 완성하는 멀티플레이 보드 게임  

+ Java/Spring Boot 기반 Back-end 서버 구축
+ Short-Polling 통신 형태의 RESTful 지향 HTTP API 서버 구축
+ State 패턴을 활용한 게임 진행 상태 관리
+ Event Bus 패턴을 활용한 Short-Polling Event Queue 구축
    - 준 실시간 요청을 처리하기 위한 비동기 처리에 대해 경험
    - Event Bus, State 등 다양한 디자인 패턴에 대해 고민, 선택하여 프로젝트에 적용
    - 효율적인 Concurrent Socket 서버에 대한 고민과 궁금증을 바탕으로 이후 학기에 관련 수업(네트워크 소프트웨어)를 청강
+ 클라이언트 레포지토리 : [Github Repository](https://github.com/owl2lwo12/MSE_2024_FA)  

## 👪 [증표 기반 단발성 모임 커뮤니티 앱 SSALON](https://github.com/lee1684/SKYTeam)
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
<img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=Spring%20Boot&logoColor=white"/>
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=Spring-Security&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![AWS Lambda](https://img.shields.io/badge/AWS_Lambda-FF9900?style=for-the-badge&logo=awslambda&logoColor=white)
![AWS S3](https://img.shields.io/badge/AWS_S3-569A31?style=for-the-badge&logo=amazons3&logoColor=white)  
**2024년 1학기 (프로젝트 완료)**    
: 팀 프로젝트(FE 2인, **BE 3인**) - SW캡스톤디자인 (아주대학교 소프트웨어학과)  
: 3D 증표 기반 단발성 모임 커뮤니티 애플리케이션  
 
+ Agile 방법론 기반 개발
    - 토의를 통해 수립한 Milestone에 맞추어 기능 개발을 진행하여 Daily Scrum을 통한 진행상황 공유의 중요성에 대해 이해
+ Java/Spring Boot 기반 Back-end 서버 구축
+ AWS S3와 연결된 증표 데이터(JSON, 이미지) 관리 및 API 개발
    - S3 파일 관리 과정에서 파일 시스템 구조 및 히스토리 관리 정책에 대해 고찰
    - S3와 프론트엔드 간 통신 과정에서 발생하는 CORS 오류에 대응하는 과정에서 CloudFront를 이용해 문제를 해결
+ AWS Lambda, MongoDB, OpenAI 활용 Embedding 기반 모임 추천 시스템 개발
+ AWS Lambda를 통해 On-demand Serverless 서비스 구현
+ AWS CloudFront로 CORS 오류 대응 및 파일 캐싱 관리
    - CloudFront 서비스를 이용하면서 발생한 이미지 문제를 통해 AWS CloudFront에서 캐싱을 통해 최적화를 이루어낸 방법에 대한 이해를 향상
+ AWS ELB 기반 EC2와 Lambda의 트래픽 분배 및 관리
+ 대내외 출품
    - 2024-1 AJOU SOFTCON SW캡스톤디자인 부문 출품 ([SOFTCON 페이지](https://softcon.ajou.ac.kr/works/works.asp?uid=1962))   

## 🗑️ [바코드 기반 재활용 도우미 앱](https://github.com/AU2302SE-Team02)
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
<img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=Spring%20Boot&logoColor=white"/>
![Firebase](https://img.shields.io/badge/firebase-a08021?style=for-the-badge&logo=firebase&logoColor=ffcd34)
![Google Cloud](https://img.shields.io/badge/GoogleCloud-%234285F4.svg?style=for-the-badge&logo=google-cloud&logoColor=white)
![Android Studio](https://img.shields.io/badge/Android_Studio-3DDC84?style=for-the-badge&logo=android-studio&logoColor=white)  
**2023년 2학기 (프로젝트 완료)**  
: 팀 프로젝트(FE 2인, **BE 2인**) - 소프트웨어공학 (아주대학교 소프트웨어학과)  
: 재활용 대상 물품의 바코드 및 사용자 위치정보에 기반한 분리배출 방법 안내 앱

+ 프로젝트 기획 제안 및 설계 ([Final Presentation PDF](https://github.com/SyingSHY/SyingSHY/blob/main/Documents/23-2%20%EC%86%8C%ED%94%84%ED%8A%B8%EC%9B%A8%EC%96%B4%EA%B3%B5%ED%95%99.pdf) ([Google Slide PPT](https://docs.google.com/presentation/d/1tt_XuQkA23njVnXtVZvJMYA55KohvQH-/edit?usp=sharing&ouid=116270002133016683325&rtpof=true&sd=true)))
    - 이후 Spring Boot와 관련해 추가적인 학습(2023 동계 모각소)으로 연계
+ Waterfall 방법론 기반 개발
    - Waterfall 방법론의 절차와 그 한계점을 직접 체험
+ Java/Spring Boot 기반 Back-end 서버 구축
    - HTTPS 활용 민감 정보의 안전한 송수신 방법에 대해 고민해보는 계기
+ Google Firebase 연동 분리배출 정보 DB 구축
+ GPS 정보 기반 Reverse Geocoding API(Naver Map API) 연계