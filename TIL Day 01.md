# TIL Day 01

> 2022년 05월 19일 목요일

## Why Git & Github?

<img src="https://user-images.githubusercontent.com/49775540/168756716-68f9aebb-380f-4897-8141-78d8403f6113.png" alt="Git로고" style="zoom:100%;"/>

+ Git
  + 분산 버전 관리 프로그램
  + 백업, 복구, 협업을 위해 사용
+ Github
  + Git을 사용하는 프로젝트의 협업을 위한 웹호스팅 서비스
  + 포트폴리오를 자랑할 수 있는 공간
  + 1일 1 commit 하기



## CLI

- Command Line Interface로 터미널을 통해 사용자와 컴퓨터가 상호 작용하는 방식을 뜻함.
- 명령어 정리
  - `mkdir test` : 'test'라는 파일 만듦
  - `touch a.txt` : 'a.txt'라는 텍스트 파일 만듦
  - `ls` : 폴더 안의 모든 내용 보여주기
  - `ls -a` : 숨김 파일까지 보여주기
  - `cd ..` : 상위 폴더로 이동
  - `cd test` : 'test'라는 폴더로 이동
  - `rm a.txt` : 'a.txt' 파일 삭제
  - `rm -r test` : 'test' 폴더와 그 내부 내용까지 전부 삭제(recursive)



## Visual Studio Code

+ Microsoft에서 개발한 텍스트 에디터의 한 종류
+ 장점
  + Windows, Mac, Linux 운영체제를 모두 지원함
  + 기존 개발 도구보다 빠르고 가벼움
  + Extension을 통해 다양한 기능을 설치할 수 있어서 무한한 확장성을 가짐
  + 무료로 사용 가능
+ Git Bash 연동하기
  + 터미널을 연다  (Ctrl + `)
  + 화살표를 누르고 Select Default Profile을 클릭함
  + Git Bash를 선택함
  + 휴지통을 눌러서 터미널을 종료하고 재시작함
  + 휴지통은 Kill Terminal로써, 터미널 자체를 아예 종료함
  + 닫기는 Close Terminal로써, 터미널을 종료하지 않고 창만 보이지 않게 만듬
  + 기본 터미널이 Git Bash로 열리는 확인함



## Markdown

+ 일반 텍스트 기반의 경량 Markup 언어

+ Markup

  Mark(글을 역할을 지정하는 표시)로 둘러싸인 언어

  Ex) HTML도 markup 언어인데, 글에 제목의 역할을 부여할 때 <h1>제목</h1>과 같이 작성함

+ 장/단점

  + 장점

    문법이 직관적이고 쉬움

    지원 가능한 플랫폼과 프로그램이 다양함

  + 단점

    표준이 없어서 사용자마다 문법이 상이함

    모든 HTML의 기능을 대신하지는 못함

+ 주의 사항

  본질은 글에 역할을 부여하는 것이므로 반드시 역할에 맞는 문법을 작성함

  Ex) 글씨을 키우기 위해서 본문에 제목의 역할을 부여하면 안 됨

+ 참고 자료

  + [Markdown Guide](https://www.markdownguide.org/basic-syntax/)
  + [문법 정리](https://gist.github.com/ihoneymon/652be052a0727ad59601)



## Git 명령어

+ 절차

  + `git config --global user.name(user.email) "github nickname(email)"` : github 이름과 이메일 설정

  + `git init` : Git으로 관리 시작

  + 파일에 변경사항 적용 (생성, 변경)

  + `git add {파일 이름}` : Staging area에 올려줌

    `git add .` : 모든 파일을 staging area에 올려줌

  + `git commit -m "메세지"` : 기록을 남김

  + `git status` : staging area에 올려놓은 명령 목록 확인

  + `git log` : commit한 내역 확인

    `git log --oneline` : 내역 별로 한 줄로 확인