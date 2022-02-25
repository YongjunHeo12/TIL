# 2일차 정리

- github 원격 저장소 생성 및 관리 

  - new repository 
  - 로컬 저장소에서 git bash 또는 vscode를 통해 git init
  - git remote add 이름 주소 를 통해 원격 저장소로 등록
  - git remote -v로 조회, git remote rm 이름 으로 삭제

  

- git에 로컬 저장소 올리기

  - git add . -> git commit -m "커밋 메시지" 
  - git status : 현재 상태 확인
  - git log --oneline : 커밋 상태를 확인

  

- github에 커밋된 로컬 저장소 올리기

  - git push 저장소이름 브랜치이름
  - 예) git push origin master



- 커밋할 때 쓸모없는 파일 제외하기
  - [이 주소에서 제외할 것 찾기(언어 및 개발환경)](https://www.toptal.com/developers/gitignore)



- github에 있는 repository 가져오기 및 push & pull과의 차이
  - git clone <repository 주소> : 연동되는 것은 아님
  - git pull <repository 주소> : 다른 사람이 원격저장소에 파일을 업데이트 하면 원격저장소와 로컬저장소의 상태를 동일하게 만들기 위해 사용
  - git push 저장소이름 브랜치이름 : local -> github
