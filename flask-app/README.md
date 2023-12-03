# Flask 웹사이트 제작
파이썬 Flask 모듈을 활용한 게시판 사이트

## 🖥 프로젝트 소개
[ 점프 투 플라스크 ] 사이트를 참조하여 만든 게시판 사이트입니다.

도커 파일을 활용하여 이미지를 빌드하고 컨테이너에 올려 사이트를 배포합니다.

## ⚙ 사용 모듈
- Python 3.12.0
- flask
- flask-wtf
- flask-migrate
- email_validator

## 📕 주요 기능
#### 회원가입 & 로그인
- 질문 & 답변 작성
- 질문 & 답변 삭제


## ⌨ 사용한 도커 명령어

    docker build -t flask-app -f ./Dockerfile .
    docker run -d -p 5000:5000 flask-app

    docker ps
    docker stop [container]

