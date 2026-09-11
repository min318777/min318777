
## About Me

- Java와 Spring Boot 기반 백엔드 개발
- MySQL 실행 계획 분석 및 인덱스 적용, 쿼리 최적화
- AWS, Docker, GitHub Actions CI/CD 기반 서비스 배포 및 운영
- k6를 활용한 부하 테스트와 성능 개선

## Tech Stacks

**Backend**

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![JPA](https://img.shields.io/badge/JPA-59666C?style=for-the-badge&logo=hibernate&logoColor=white)
![QueryDSL](https://img.shields.io/badge/QueryDSL-black?style=for-the-badge)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black)

**Database & Cache**

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Flyway](https://img.shields.io/badge/Flyway-CC0200?style=for-the-badge&logo=flyway&logoColor=white)

**Infrastructure**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)

**Monitoring & Testing**

![k6](https://img.shields.io/badge/k6-7D64FF?style=for-the-badge&logo=k6&logoColor=white)

**Collaboration**

![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
## Featured Project

꼬랑지(kkorangji) - 반려동물 일상 공유 및 실종,제보 소셜 서비스

https://github.com/min318777/kkorangji

Java, Spring Boot, MySQL, Redis, AWS, JPA, Query DSL 기반 RESTful API 개발

- 게시글 목록 조회에 인덱스를 적용해 100만 건 데이터 기준 응답 속도 1,100ms → 20ms 단축
- SSE 실시간 알림에 Heartbeat 전략을 도입하여 비정상 연결 종료 시 좀비 커넥션 문제 해결
- 조회수 업데이트를 DB 원자적업데이트 방식으로 전환하여  동시성으로 인한 Lost Update 해결
- 인기글 목록 조회 방식에 Redis를 도입하여 점수 기반으로 정렬된 데이터를 인메모리 저장소에서 빠르게 조회할 수 있도록 개선

조각조각(Jogakjogak) - 이력서, 채용공고 분석 기반 취업 준비 체크리스트 서비스

https://github.com/min318777/Jogakjogak

Java, Spring Boot, MySQL, Redis, AWS, JPA, OAuth2, JWT, Spring Security, Dokcer (팀 프로젝트, BE 3인)

- JWT Access/Refresh 이중 토큰 전략에 Redis TTL을 적용해 만료 토큰 자동 삭제 및 인증 쿼리 부하 감소
- Refresh Token Rotation으로 토큰 재사용을 감지해 탈취 의심 시 해당 사용자의 전체 세션을 즉시 무효화
- Gemini 2.0 API로 이력서, 채용공고를 분석해 부족한 점을 체크리스트 형태로 자동 생성
- CORS 화이트리스트와 HttpOnly 쿠키 기반 인증으로 프론트(Vercel), 백엔드(EC2) 분리 배포 환경에서 안전한 크로스 오리진 통신 구성


## Contact

alsquddlf1@gmail.com
