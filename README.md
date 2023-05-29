<a name="project-name"></a>

# Project Name

- [2023년 서울 열린데이터광장 공공데이터활용 모바일 앱/웹 경진대회 프로젝트](https://mediahub.seoul.go.kr/gongmo/2000334)
- 개발 기간 : 23.04.05 ~ 23.05.31

<a name="list"></a>

## 목차

- [Project Name](#project-name)
  - [목차](#목차)
  - [프로젝트 소개](#프로젝트-소개)
  - [개발과정](#개발과정)
  - [팀 구성원](#팀-구성원)
  - [역할 분담](#역할-분담)
  - [기술 스택](#기술-스택)
  - [.env 설정](#env-설정)

## 프로젝트 소개

- [상세기획서 보기](#)

## 개발과정

- **Github**

  - Issue, Project로 관리했습니다.
  - protected branch를 설정하여, PR을 통한 코드 리뷰를 진행했습니다.
  - Frontend, Backend, AI 별 담당자를 두고, 레포지토리를 따로 관리했습니다.
  - 담당자가 아닌 사람은 fork를 통해 작업하고, PR을 통해 코드 리뷰를 진행했습니다.

- **배포 직전의 Commit과 PR 기록을 보시려면 각 레포지토리를 확인해주세요.**

  - [Frontend](https://github.com/kimyoo04/seoul-competition-frontend)
  - [Backend](https://github.com/beginner0107/seoul-competition-backend)
  - [AI](https://github.com/Pang-dachu/seoul-competition-ai)

## 팀 구성원

<table>
<tr>
    <td align="center"><a href="https://github.com/kimyoo04"><img src="https://avatars.githubusercontent.com/u/58503130?v=4" width="100px;" alt="kimyoo04"/>         <br /><sub><b>kimyoo04</b><br>
    <td align="center"><a href="https://github.com/Pang-dachu"><img src="https://avatars.githubusercontent.com/u/54354769?v=4" width="100px;" alt="Pang-dachu"/>         <br /><sub><b>Pang-dachu</b><br>
    <td align="center"><a href="https://github.com/chae-zero"><img src="https://avatars.githubusercontent.com/u/115343657?v=4" width="100px;" alt="chae-zero"/>         <br /><sub><b>chae-zero</b><br>
    <td align="center"><a href="https://github.com/beginner0107"><img src="https://avatars.githubusercontent.com/u/81161819?v=4" width="100px;" alt="beginner0107"/>         <br /><sub><b>beginner0107</b><br>
    <td align="center"><a href="https://github.com/kawkmin"><img src="https://avatars.githubusercontent.com/u/86940335?v=4" width="100px;" alt="kawkmin"/>         <br /><sub><b>kawkmin</b><br>
</tr>
</table>

## 역할 분담

- **Leader**
  김유

- **Infra**
  김유, 안승주

- **Frontend**
  김유, 정채영

- **Backend**
  안승주, 곽민성

- **AI**
  김인재

## 기술 스택

![인프라구조](https://github.com/kimyoo04/seoul-competition-all/assets/58503130/cfa63cf8-2a32-4ef7-8b7b-10ddd3a25623)

:computer: **Infra ( EC2 t2.large / Nginx / Docker-compose )**

:computer: **Front-End ( Nextjs / Typescript(TS) / TailwindCSS / Redux-Toolkit )**

:computer: **Back-End ( Spring boot / Spring Data Jpa / MySQL )**

:computer: **AI ( Fastapi / Scikit-learn / Konlpy / Transformer / chatGPT )**

## .env 설정

```
# NGINX (컨테이너 적용 X)
NGINX_HOST=
NGINX_PORT=
NGINX_SSL_PORT=
NGINX_SERVER_NAME=
NGINX_SSL_CERTIFICATE=
NGINX_SSL_CERTIFICATE_KEY=
NGINX_SSL_TRUSTED_CERTIFICATE=

# NEXTJS
NEXT_PUBLIC_ENV_API_DOMAIN=
NEXT_PUBLIC_ENV_API_URL=
NEXT_PUBLIC_ENV_DOMAIN=

# SPRING
SPRING_DATASOURCE_URL=
SPRING_DATASOURCE_USERNAME=
SPRING_DATASOURCE_PASSWORD=
SPRING_FIFTY=
SPRING_SENIOR=
SPRING_API_KEY=

# MYSQL
MYSQL_DATABASE=
MYSQL_ROOT_PASSWORD=
MYSQL_ROOT_HOST=
MYSQL_USER=
MYSQL_PASSWORD=

# FASTAPI
FASTAPI_API_DOMAIN=
FASTAPI_API_URL=
FASTAPI_OPENAI_KEY=
```
