# Git을 쓰는 이유
- 코드의 수정을 관리해야한다
- 잔뜩 쌓인 파일들을 관리해야 한다
- 개발은 혼자 하는 일이 아니다
- 버전 관리가 필요하다
- 어떤파일이 수정됐는지 / 누가 수정했는지 / 언제 수정됐는지 / 어떻게 수정됐는지 / 이 모든걸 추적하고 원하는 상태의 코드를 사용하기 위해 git을 사용한다
# Git이란?
- 버전 관리 및 협업을 위해 사용하는 오픈소스 소프트웨어 

# Git의 영역
- Working Directory
- Staging Area
- Repository

# Git으로 파일 관리하기
1. 디렉토리에 Git 저장소를 만들기
- git init
2. Git으로 관리할 대상 등록하기
- git add
3. 파일 수정 후 로컬 저장소로 옮기기
- git commit 

# GitHub에서 가능한 것들
- 이슈트래킹
- 코드 리뷰
- Github Actions로 CI/CD
- Github Projects로 프로젝트 업무 관리

## Git으로 파일관리하기
### 모든파일 한번에 등록
- git add.
### 하나씩 등록
- git add <파일명>
### unstage로 되돌리기
- git rm --cached \<file>

파일 수정 후 로컬 저장소로 옮기기
- git commit

## Commit Message - type
- 새로운기능을 추가한 경우 : feat
- 기존 코드를 개선한 경우 : refactor
- 버그를 수정한 경우 : fix
- 코드 외의 설정을 바꾼 경우 : chore
- 문서화 : docs
- 테스트 코드 : test

# Git에 커밋하기
git commit -m "<commit message>

# GitHub에 올리기 앞서
- git remote add origin <주소>
- git branch -M main
- git push -u origin main

# GitHub에 올리기
- git add <파일명>
- git commit -m "commit message"
- git push origin main


<https://github.com/honghong0303/honghong0303>