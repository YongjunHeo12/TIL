# 2일차 정리

- 1일차 복습

- github가입

  - TIL repository 생성(remote)
  - TIL repository 연결(romote - local)

  

- github에 업로드 하는 과정

  - 저장/touch > add > commit > push
  
    - touch : bash 언어로 파일 만들기
    - git add : 파일을 스테이징 영역에 추가
    - git add. : 현재 디렉터리에 있는 파일을 전부 스테이징 영역에 추가
    - git commit -m "message" :  작업한 것을 확정시키고 메시지를 저장
    - git push origin master  : origin이라는 원격저장소의 master 브랜치에 푸쉬
  
    


- .gitignore

  - [이 주소에서 제외할 것 찾기(언어 및 개발환경)](https://www.toptal.com/developers/gitignore)

  

- clone, pull

  - clone : github에 있는 repository 로컬로 가져오기 (연동 x)
  
  - push <-> pull 
    - push: local -> github로 
    - pull: 다른 사람이 원격저장소에 업데이트한 파일이 있을 때, 원격저장소와 내 로컬저장소의 상태를 동일하게 만들기 위해 사용
    
    
  


- git log : 커밋 이력 확인하기 




  - --oneline : 한 줄로 요약




- git status: 어느 영역에 있는지 확인하기
