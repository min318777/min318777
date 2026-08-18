# 민병일 👋

안정적인 서비스와 확장 가능한 구조를 고민하는 백엔드 개발자입니다.
트랜잭션 경계, 캐시 정합성, 장애 상황을 고려한 설계에 관심이 있습니다.

- 🐾 Java / Spring Boot 기반 백엔드 개발
- 🗄️ MySQL 쿼리 최적화 & QueryDSL, Redis 캐시 적용
- 🔔 Spring Event + Async + SSE 기반 실시간 알림 설계
- ☁️ Docker / GitHub Actions 기반 CI-CD 및 배포 자동화

## Tech Stack

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)

## 🐾 Featured Project — 꼬랑지 (kkorangji)

반려동물 소셜 플랫폼 · 자랑/실종 게시글, 댓글, 좋아요, 실시간 알림

- **Stack**: Java 17, Spring Boot 3.4.5, MySQL + JPA/QueryDSL, Redis, AWS S3, Prometheus/Grafana
- 자랑 게시글 · 실종 게시글 작성/조회, 위치 기반 검색(Hibernate Spatial) 지원
- Redis 캐시 + CacheErrorHandler로 캐시 장애 시 DB Fallback 처리
- Spring ApplicationEvent + `@Async` + SSE 기반 실시간 알림
- OAuth2(Google) + JWT 기반 인증, S3 Presigned URL 기반 이미지 업로드
- Docker + GitHub Actions → GHCR → EC2 배포 파이프라인

🔗 [Repository](https://github.com/min318777/kkorangji)

## GitHub Stats

<p>
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=min318777&show_icons=true&theme=default&hide_border=true" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=min318777&layout=compact&hide_border=true" />
</p>

![Visitor Count](https://komarev.com/ghpvc/?username=min318777&color=blueviolet&style=flat-square&label=Profile+Views)

## Contact

📫 alsquddlf1@gmail.com
