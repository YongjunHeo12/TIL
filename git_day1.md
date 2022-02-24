# CLI

- 커맨드라인 명령어

  ```bash
  # 디렉토리 생성
  mkdir
  # 디렉토리 이동
  cd
  # 파일을 생성
  touch
  # 디렉토리 안 리스트를 확인
  ls
  # 제거
  rm
  ## -r 옵션 : 재귀적 
  ## -rf 옵션 : 강제 삭제
  # 이동/이름변경
  mv
  # 현재의 경로를 보여줌
  pwd
  # 화면 깨끗이/스크롤 올리기
  clear
  ctrl + l 
  ```

  

# 마크다운 

- 마크다운과 마크업
  - 마크업: html -> 개발자 도구로 확인 (태그)
  - 마크다운 : 쉽고 가볍게 적용 가능

- #을 이용한 제목 표현
  -  #을 6개까지 해서 표현할 수 있음

- 목록 표현

   - 순서가 없는 목록 -> `-`, `+`, `*` 을 이용
   - 순서가 있는 목록 -> 1, 2, 3을 이용
   - shift + tab을 통해 내어쓰기 가능

- 강조하기

   - *기울임* : `*글자*` or `_글자_` or ctrl + i
   - **굵게**: `**글자**` 혹은 `__글자__`
   - ~~취소선~~: `~~글자~~` 
   - <u>밑줄</u>: ctrl+u, `<u>글자</u>`

- 코드(code)

   - `인라인 코드` : 백틱(`)으로 한줄 코드를 묶어주기
   - 코드 블록: 여러 줄 코드를 백틱 3개(```)로 묶어주기

   ```python
   print("hello")
   ```

- 링크

   - [표시글자]\(이동할 주소)
   - [git 특강 메인 페이지](https://www.notion.so/hphk/Git-5-_E-22-02-23-22-02-25-1b97e73779554044b56f15cd57693e9a)

- 이미지 

   - ![대체할 텍스트](이미지 주소)
      - 대체 텍스트란 이미지를 정상적으로 가져오지 못하였을때 표시

- 인용

   - 주석 혹은 인용문을 작성할 때 사용
   - `>` 를 사용하여 인용, > 갯수에 따라 중첩가능

   > 인용문 작성1
   >
   > > 중첩
   > >
   > > > 중첩

- 수평선

   - `---`,`***`,`___`

- 표

   - ctrl+t, command+t
   
   - |      |      |      |
      | ---- | ---- | ---- |
      |      |      |      |
      |      |      |      |
      |      |      |      |
   
      
   

# git 기초

- git의 3공간
  - working directory(로컬에서 작업한 곳), staging area(git add한 부분), commits(git commit)

- git 명령
  - git init
    - 맨처음 1회, 절대 홈폴더에서 하지 않는다.
    - git init한 폴더의 하위 폴더에서 절대 git init하지 않는다.
  - git add 
  - git commit -m "메시지"
  - git status : 파일 상태를 확인
  - git log : 커밋 내역 확인
    - --oneline : 한줄 출력

- git 초기 설정

  - git config

    ```bash
    git config --global user.name "유저명"
    git config --global user.email "유저 이메일" # 깃허브에서 사용
    ```

# TIL

 `Today I Learned`: 배웠던 내용들 기록하는 repository

