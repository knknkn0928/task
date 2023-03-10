# task

## 과제방에 repo 주소로 업로드

1. task repository 포크로 본인 repository에 복사
2. 내려 받기해서 해당 README.md 문서 수정
3. 오늘까지 배운 git 내용 마크다운 형식으로 __잘__ 정리
  _markdown-cheetseat 참고_
4. 본인 repository에 업로드
5. 로컬 저장소 내용도 캡쳐해서 함께 업로드

이 아래로 내용 작성
-

# Git 깃 #

## Git깃이란? ##

리눅스 운영 체제 개발자인 리누스 토르발스가 만든 소프트웨어 소스 코드 관리 시스템으로 <b>버전관리, 백업, 협업</b>을 목적으로 사용된다.

## Github란? ##

인터넷 온라인의 서버를 통해 백업과 협업, 장소를 옮긴 작업을 용이하게 만드는 저장소.

## 기본 설정 ##

<b>git init</b> 폴더에 로컬 저장소 .git 생성

<b>git config --global user.name "ID"</b> 아이디를 등록

<b>git config --global user.email "Email"</b> 이메일을 등록

위를 통해 github 계정과 연동될 수 있도록 설정


## 파일 등록-커밋 ##

<b>git add "파일명.확장자", git add . </b> 파일을 개별추가 / 전체추가

<b>git commit -m "이건 첫번째로 할때"</b> 커밋해서 버전 생성

<b>git commit -am "<i>이건 두번째 커밋부터</i>"</b> 추가와 커밋을 한번에


## 이력확인 ##

<b>git status</b> 현재상태 확인

<b>git config --list</b> 설정정보 확인

<b>git log</b> 커밋기록 확인


### <b>log + 명령어</b> ###

<b>--oneline</b> 한줄 요약된 커밋기록

<b>--graph</b> 그래프 포함된 커밋기록

<b>--all</b> 그동안 커밋된 기록과 생성요소 전부 확인


## 브랜치 ##

<b>git branch " "</b> 명령 브랜치 생성

<b>git switch " "</b> 명령 브랜치로 이동

<b>git merge " "</b> 현재 브랜치를 명령 브랜치와 병합

<b>git branch -a , --list</b> 생성된 브랜치 리스트 확인


## github에서 복사 ##

<b>git clone http://github.com~ </b> 내 로컬 저장소로 복사

<b>git clone http://github.com~ .</b> 폴더를 미리 생성해둔 경우


## github 공유 ##

<b>git push -u origin "main"</b> main 브랜치에 업로드

<b>git push origin "브랜치"</b> 다른 브랜치에 업로드

<b>git pull origin "main"</b> main 브랜치에서 다운로드

<b>git pull origin "브랜치"</b> 다른 브랜치에서 다운로드