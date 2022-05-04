### ✏️ [프로젝트 시작] Readme.txt

---

**프로젝트 소개**

 최근 ‘코로나19’이후 소통, 공감하려는 욕구가 커져, 실시간으로 다른 사람과 소통하는 서비스의 수요가 증가하였다. 영화에 대한 정보와 이 영화를 본 다른 사람의 관점을 알고 싶어 리뷰를 찾게 되는 이용자가 있으며, 이러한 이용자들의 대다수는 다른 사람과 영화 내용에 관한 이야기하고 싶어 한다. 기존 영화 평점 사이트의 경우 단순한 정보만 얻을 수 있을 뿐 사용자들 간에 소통할 수 있는 창구가 부족하였다. 또한 서버 접속인원이 많을 때 대기시간이 길거나 데이터를 불러오지 못하여, 필요한 정보를 찾는데 불편함을 겪었다.

 본 프로젝트는 단순 영화에 대한 정보, 리뷰 조회뿐만 아니라 채팅방을 통해 다른 사용자들과 즉각적인 소통 창구를 추가 제공하며, 원활한 서버 환경을 제공해 실시간으로 소통이 가능한 영화 플랫폼을 제작한다.

**프로젝트 목표**

영화 리뷰 검색 및 실시간 채팅이 가능한 사이트

**지원 기능**

- [인증 기능](https://github.com/K5S-TEAM/k5smovie-auth)
- [영화 정보 기능](https://github.com/K5S-TEAM/k5smovie-Info)
- 채팅 기능
- [리뷰 기능](https://github.com/K5S-TEAM/HotMovie)
- [유저 편의 기능(마이페이지 등)](https://github.com/K5S-TEAM/k5smovie-member-convenience)

**프로젝트 문서**



**프로젝트 전체 구상도**



**사용 기술 스택**



- 크롤링 : Python + BeautifulSoup
- 프론트 엔드 : HTML + JS + CSS
- 백엔드 : Springboot, STOMP, JPA, Gradle, postman
- 데이터베이스 : Amazon RDS(Mysql), Amazon ElasticCache(Redis), Amazon S3
- 인프라 : Terraform(IaC), Amazon Elastic Kubernetes Service(EKS), Amazon EC2, Amazon Route53, Cluster Autoscaler, AWS ALB Ingress Controller, Metrics server
- CI/CD : Jenkins, ArgoCD, Github, Amazon Elastic Container Registry
- 모니터링 : Grafana, Prometheus, Lok, Promtai
- MSA : Istio, Kiali, Jaeger

**기대 효과 (AS-IS TO-BE)**

- **AS-IS**
    - 기존 영화 평점 사이트의 경우 단순한 정보만 얻을 수 있을 뿐 사용자들 간에 소통할 수 있는
    공간이 부족하였음.
    - 서버 접속 인원이 많을 때 대기시간이 길거나 데이터를 불러오지 못하여, 필요한 정보를
    찾는데 불편함을 겪음.
- **TO-BE**
    - 단순 영화에 대한 정보, 리뷰 조회뿐만 아니라 채팅방을 통해 다른 사용자들과
    즉각적인 소통 창구를 추가 제공.
    - 원활한 서버 환경을 제공하여 실시간으로 소통이 가능하도록 해 사용자의 불편함이
    없도록 한다.

### ⚙️ [프로젝트 개발 및 추진체계]

---

### ♟️Member
정진용(팀장)|김현구|김찬영|송영민|
:-:|:-:|:-:|:-:|
<img src="https://avatars.githubusercontent.com/u/32133264?v=4" width="200">|<img src="https://avatars.githubusercontent.com/u/65819843?v=4" width="200">|<img src="https://avatars.githubusercontent.com/u/46098949?v=4" width="200">|<img src="https://avatars.githubusercontent.com/u/24770814?v=4" width="200">|
[Github](https://github.com/LittleSamakFox)|[Github](https://github.com/presentnine)|[Github](https://github.com/ChanYoung-dev)|[Github](https://github.com/SYMo-oSYM)|

### ♟️Contribution
- `정진용` &nbsp; 보고서 작성 • 인프라 설계 • CI/CD 파이프라인 설계 • 모니터링 설계
- `김현구` &nbsp; 아키텍쳐 설계 • 유스케이스 설계 • 인증 기능 구현 • 유저 편의 기능 구현
- `김찬영` &nbsp; 유스케이스 설계 • 리뷰 기능 구현
- `송영민` &nbsp; 유스케이스 설계 • 영화 & 채팅 기능 구현 • 영화 정보 크롤링
