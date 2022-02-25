# Branch

1. git branch
- 브랜치 조회, 생성, 삭제 관련 명령어
```bash
# 브랜치 목록 확인
git branch

# 브랜치 생성
git branch 신규브랜치명

# 브랜치 삭제
git branch -d 브랜치명
git branch -D 브랜치명 # 강제삭제 옵션
```

2. git switch
- 다른 브랜치로 이동하는 명령어
```bash
# 브랜치 이동
git switch 다른브랜치명

# 브랜치 생성 후 이동
git switch -c 다른브랜치명
```