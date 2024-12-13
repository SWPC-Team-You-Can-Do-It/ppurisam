<h1>음성 인식 기반 AI 문자 및 이미지 전송 서비스 PPURISAM</h1>

![header](https://capsule-render.vercel.app/api?type=waving&color=31A575&height=320&text=PPURISAM&fontSize=80&desc=AI와%20음성인식을%20이용한%20문자%20전송&descSize=40&descAlignY=70&fontColor=FFFFFF&fontAlignY=40&animation=fadeIn)

<br>

## 📝 목차
- [미디움](#미디움)
- [프로젝트 소개](#프로젝트-소개)
- [주요 기능](#주요-기능)
- [시스템 아키텍처](#시스템-아키텍처)
- [기술 스택](#기술-스택)
- [ERD](#ERD)
- [API](#API)
- [사용방법](#사용방법)
- [개발 기간](#개발-기간)
- [팀 구성](#팀-구성)

<br>

## 📒 미디움
🔗 [[https://medium.com/@bkw54570/1201fcd2ced2](https://kittae.tistory.com/17)](https://kittae.tistory.com/17)

<br>

## ✉️프로젝트 소개
- 본 프로젝트는 [**SW 프리캡스톤 디자인 교과목**]을 통해 [**다우기술**]과 연계하여 진행되었습니다.
- [**PPURISAM**] 프로젝트의 목표는 '**누구나 쉽게 이용할 수 있는 서비스**'입니다.
- 기본적인 웹서비스 기능 이외에도 사용자의 편리성이라는 관점에서 **음성인식**과 **AI를 이용한 이미지 생성**, **챗봇**을 추가로 구현하였습니다.

<br>

## ✨주요 기능
- 페이지는 문자 전송 / 주소록 / 발송조회 / 마이페이지 로 구성되어, 기본적인 문자 서비스를 제공하고 있습니다
- 문자 전송 시, 사용자는 작성하고 싶은 문자에 대해 간략하게 입력하여 AI를 통한 **문자 템플릿**과 관련된 **이미지**를 제공받습니다.
- 그리고 이러한 과정 중 **음성인식**을 통해 키보드 입력을 최소화하여, 사용자의 접근성을 높였습니다.
- 또한, **챗봇** 서비스를 통해 페이지 이동없이 간편하게 문자 전송 서비스를 제공하여, 사용자의 편의성을 더욱 개선하였습니다.

<br>

### [회원가입&로그인]
![회원가입, 로그인](https://github.com/user-attachments/assets/7387722c-c333-4ba9-b0af-02b51612b086)

<br>

### [홈 화면]
![홈화면](https://github.com/user-attachments/assets/30d24a1a-3b76-4dc4-a680-39f73eb4e774)

<br>

### [주소록]
![주소록2](https://github.com/user-attachments/assets/a43ec374-03e4-4bd8-927f-421a553e8cce)

<br>

### [문자 보내기]
![문자 보내기](https://github.com/user-attachments/assets/f9f022b0-6826-4a81-b655-7d7a8f97b2d2)

<br>

#실제 문자 화면

![문자보내기 문자](https://github.com/user-attachments/assets/d2c94491-5073-4adf-bd97-7090814a93e8)


<br>

### [발송조회]
![발송조회](https://github.com/user-attachments/assets/fb899b93-e7a7-4686-8623-de05b4ef40e2)

<br>


### [챗봇]
![챗봇](https://github.com/user-attachments/assets/454a414e-9591-41af-9df0-e678a71fffa8)

#실제 문자 화면

![챗봇 문자](https://github.com/user-attachments/assets/8ce65e4d-573f-463c-a39f-4f35af38971d)

<br>


### [마이페이지]
![mypage](https://github.com/user-attachments/assets/63e86ab7-fe6e-4a45-bc7f-f2264d2b3210)

<br>

## ⚙️시스템 아키텍처
![image](https://github.com/user-attachments/assets/50cb8354-b514-4c78-b123-8aedff0eb135)


<br>

## 💻기술 스택

- Front-end

|                             React                              |                         Javascript                          |                             CSS                              |                             Vite                              |
|:--------------------------------------------------------------:|:-----------------------------------------------------------:|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| ![My Skills](https://skillicons.dev/icons?i=react&theme=light) | ![My Skills](https://skillicons.dev/icons?i=js&theme=light) | ![My Skills](https://skillicons.dev/icons?i=css&theme=light) | ![My Skills](https://skillicons.dev/icons?i=vite&theme=light) |  
<br>

- Back-end

|                                                                    Springboot                                                                    |                             MySQL                              |                                                                       ELK+Beats                                                                        |                             Nginx                              |                                                                 Prometheus / Grafana                                                                  |
|:------------------------------------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------:|:------------------------------------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------:|:-----------------------------------------------------------------------------------------------------------------------------------------------------:|
| <img src="https://github.com/user-attachments/assets/58e04523-c570-4d5d-b37c-a286fa74f0e6" width="50" height="50" style="border-radius: 13px;" > | ![My Skills](https://skillicons.dev/icons?i=mysql&theme=light) | <img src="https://github.com/user-attachments/assets/368e20df-4a89-4a7d-9da1-126358f78180" width="50" height="50" style="border-radius: 13px;" > | ![My Skills](https://skillicons.dev/icons?i=nginx&theme=light) | ![My Skills](https://skillicons.dev/icons?i=prometheus&theme=light)&nbsp;&nbsp;&nbsp;![My Skills](https://skillicons.dev/icons?i=grafana&theme=light) |
<br>

- 서비스 배포 및 실행 환경

|                                                                     AWS Ec2                                                                      |                             Docker                              |
|:------------------------------------------------------------------------------------------------------------------------------------------------:|:---------------------------------------------------------------:|
| <img src="https://github.com/user-attachments/assets/7c5ae4ed-14c1-4830-adc5-d6d49bc18663" width="50" height="50" style="border-radius: 13px;" > | ![My Skills](https://skillicons.dev/icons?i=docker&theme=light) |
<br>

- 버전 및 이슈관리

|                      Github, Github Issues                      |
|:---------------------------------------------------------------:|
| ![My Skills](https://skillicons.dev/icons?i=github&theme=light) |
<br>

- 협업 툴

|                             Discord                              |                             Notion                              |
|:----------------------------------------------------------------:|:---------------------------------------------------------------:|
| ![My Skills](https://skillicons.dev/icons?i=discord&theme=light) | ![My Skills](https://skillicons.dev/icons?i=notion&theme=light) |
<br>

- 디자인

|                             Figma                              |
|:--------------------------------------------------------------:|
| ![My Skills](https://skillicons.dev/icons?i=figma&theme=light) |
<br>

<br>

## 💾 ERD
<img src="https://github.com/user-attachments/assets/db930415-1ebd-4161-86b2-5a218c2fd607">
<br>
<br>

## 🌐 API
<img src="https://github.com/user-attachments/assets/b7f46df1-b48f-4069-9129-7230b10cff81">
<img src="https://github.com/user-attachments/assets/461211d8-3b34-4db8-882b-a11bd565ccba">
<br>
<br>

## 📊 모니터링&로그관리
<img width="1285" alt="image" src="https://github.com/user-attachments/assets/54b7b08f-2e55-48d1-9789-a64fa00e3b05">



![image](https://github.com/user-attachments/assets/82359acc-eafb-4734-ad27-3d82fe7d20f2)
<br>

## 사용방법 - 해상도는 1512x982에서 정상적으로 보입니다!
### 처음부터 서브모듈을 고려하여 한번에 클론
```bash
git clone --recurse-submodules https://github.com/SWPC-Team-You-Can-Do-It/ppurisam.git
```

### 이미 일반 클론을 받은 경우 서브모듈 초기화
```bash
git submodule update --init --recursive
```

### 프로그램 실행 전 ppurisam, Frontend, Backend에 .env파일 작성
### Backend/src/main/resources/ 안에 application.properties파일 작성

### 도커 설치 확인
```bash
docker --version
docker-compose --version
```

### 설치되어있지 않은 경우
```bash
sudo apt install -y docker.io
sudo curl -L "https://github.com/docker/compose/releases/latest/download/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
sudo chmod +x /usr/local/bin/docker-compose
```

### 프로그램 실행
```bash
docker compose up -d --build
```

### 프로그램 종료
```bash
docker compose down
```


## 📆개발 기간
- 2024-09-20 ~ 2024-11-28
  <br>

## 🤝팀 구성

|                                                                           **배건우**                                                                           |                                                                             **진기태**                                                                             |                                       **박진성**                                        |                                       **박지원**                                        |                                       **장원진**                                        |
|:-----------------------------------------------------------------------------------------------------------------------------------------------------------:|:---------------------------------------------------------------------------------------------------------------------------------------------------------------:|:------------------------------------------------------------------------------------:|:------------------------------------------------------------------------------------:|:------------------------------------------------------------------------------------:|
|                                                         <center>팀장<br>Frontend<br>Backend</center>                                                          |                                                              <center>Frontend<br>Backend</center>                                                               |                               <center>Backend</center>                               |                               <center>Backend</center>                               |                              <center>Frontend</center>                               | 
| [<img src="https://github.com/user-attachments/assets/a75ab739-e053-4f9d-89f7-7bf33cecb115" height=150 width=150> <br/> @bkw535](https://github.com/bkw535) | [<img src="https://github.com/user-attachments/assets/b65e1842-38b8-4164-8319-12b5393e479a" height=150 width=150> <br/> @sensesis](https://github.com/sensesis) | [<img src="https://github.com/user-attachments/assets/8efdbace-bc94-4d33-a555-a9ecf256a94e" height=150 width=150> <br/> @Jinseong01](https://github.com/Jinseong01) | [<img src="https://github.com/user-attachments/assets/34bef6f6-eced-4a4a-8fa0-5ad57f2fc2ec" height=150 width=150> <br/> @jiwonp7747](https://github.com/jiwonp7747) | [<img src="https://github.com/user-attachments/assets/ce943540-5c2c-4892-90f9-847da34c70da" height=150 width=150> <br/> @wonjinjang](https://github.com/wonjinjang) 

