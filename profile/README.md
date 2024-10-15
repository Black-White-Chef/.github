# Black-White-Chef

<p align="center">
    <img src="https://github.com/user-attachments/assets/77d0e824-f9ef-425d-8572-f3bd44332ccc" alt="bw-chef-logo" width="500">
</p>




<p align="center">
    <a href="https://hits.seeyoufarm.com">
        <img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FBlack-White-Chef%2Fhit-counter&count_bg=%23E8E8C1&title_bg=%23D15693&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false" alt="hits">
    </a>
</p>
<br>

## 배포 주소
개발 버전: 

프론트 서버: 

백엔드 서버: 



## 웹 개발 팀 소개
|  손석영  |  조준영  |  김수진  |
|:--------:|:--------:|:--------:|
|          |<img src="https://github.com/user-attachments/assets/f7371813-8e6b-4b26-8b78-5d8cbaefca8d" width="100">|<img src="https://github.com/user-attachments/assets/7e423526-57de-4637-adc8-c3d0530d89f4" width="100">|
|github.com/coder-ssy|github.com/JunYoung02|github.com/sjkim15|
|Backend<br>Devops|Frontend|Frontend|



## 프로젝트 소개
흑백 요리사라는 넷플릭스 프로그램이 방영된 후 출연자들의 식당을 찾아 가는 손님들이 많이 늘어났습니다. 
백수저 20명, 흑수저 20명 총 40명의 출연자들의 식당을 찾기 쉽게 정리해 두었습니다. 

# 시작 가이드
### Requirements
For building and running the application you need:
- Node.js 20.17.0
- yarn 1.22.22

### Installation
```bash
$ git clone https://github.com/Black-White-Chef/full-project.git
$ cd full-project
```

#### Env Settings
```
DATABASE_NAME=
DATABASE_USER=
DATABASE_PASS=
DATABASE_PORT=
SECRET_KEY=

DJANGO_ALLOWED_HOSTS=
DEBUG=

CORS_ALLOWED_ORIGINS=
```

#### Backend
```bash
$ cd backend
$ docker compose --build
$ chmod +x wait-for-it.sh
```

#### Frontend
```bash
$ cd frontend
$ yarn
$ yarn build
$ docker compose up --build
```

# Stacks
### Frontend
<span>
<img src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=black">
<img src="https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white">
<img src="https://img.shields.io/badge/Yarn-2C8EBB?style=for-the-badge&logo=yarn&logoColor=white">
<img src="https://img.shields.io/badge/SCSS-CC6699?style=for-the-badge&logo=sass&logoColor=white">
</span>


### Backend
<span>
<img src="https://img.shields.io/badge/python-79b64c?style=for-the-badge&logo=python&logoColor=white">
<img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
</span>


### DevOps
<span>
<img src="https://img.shields.io/badge/GitKraken-179287?style=for-the-badge&logo=gitkraken&logoColor=white">
<img src="https://img.shields.io/badge/django-092E20?style=for-the-badge&logo=django&logoColor=white">
<img src="https://img.shields.io/badge/Gunicorn-bbbcd9?style=for-the-badge&logo=gunicorn&logoColor=white">
<img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white">
</span>


### Monitoring
<span>
<img src="https://img.shields.io/badge/Prometheus-ff72ba?style=for-the-badge&logo=Prometheus&logoColor=white">
<img src="https://img.shields.io/badge/grafana-%23F46800.svg?style=for-the-badge&logo=grafana&logoColor=white">
</span>


### Etc
<span>
<img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white">
<img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white">
<img src="https://img.shields.io/badge/Figma-c298bb?style=for-the-badge&logo=figma&logoColor=white">
<img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white">
<img src="https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white">
<img src="https://img.shields.io/badge/GitKraken-179287?style=for-the-badge&logo=gitkraken&logoColor=white">
</span>


# 화면 구성 📺
### 💮 메인화면
![image](https://github.com/user-attachments/assets/d03e7c25-c0a7-474a-a58c-29900180ad99)
![image](https://github.com/user-attachments/assets/a68f9f2f-5971-4b4d-adff-3891f87305dc)


### 💮 응원 메시지 작성 화면
![image](https://github.com/user-attachments/assets/20a29bc7-9c43-47d7-bead-b8b19b1b2a56)




### 💮 피드백 메시지 작성 화면
![image](https://github.com/user-attachments/assets/451ba05f-71a6-4cb6-a443-55813fa1b4c6)




# 주요 기능 🗃️
⭐ 요리사 리스트 출력
- 40명의 요리사들의 프로필 사진 제공
- 마우스를 hover하면 해당 요리사의 한 줄 소개와 이름이 보인다
- 사진을 클릭하면 해당 요리사의 식당 지도로 이동

⭐ 응원 모달 기능
- 닉네임 생성 후 응원 메시지 작성
- slider로 사용자들이 작성한 응원 메시지가 돌아간다


⭐ 피드백 모달 기능
- 페이지 접속 후 30 초 뒤에 피드백 모달 창이 뜬다
- 피드백 작성


⭐ 영어 변경 기능
- 화면 오른쪽 상단에 있는 English버튼을 누르면 영어 버전으로 변경
