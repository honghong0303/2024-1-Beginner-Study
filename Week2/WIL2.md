# 오늘의 토픽
- GitHub의 Fork/Star
- Issue
- Branch
- Pull Request
- Merge

## Fork
- 다른 사용자의 repositor를 자신의 계정으로 복사하여 독립적으로 수정하고 관리

## Star
- 관심있는 repository나 프로젝트에 star를 달아 "북마크"와 같이 관리

## Issue 
- repository에서 작업 계획, 토론 및 추적을 위해 활용

## Branch
- 기존 브랜치에서 분기되어 생성되는 별도의 작업공간
- fork와 달리 같은 repository에 생성됨
  
### Branch Naming Convention
- "type/<issue 번호>-<간략한 설명>"

## Pull Request
- 분기된 Branch를 다시 병합하기 위한 절차ㅣ
- 새로운 변경을 제안하거나 병합 시 발생하는 충돌을 해결
- Merge에 앞서 코드 리뷰

## Merge
3가지 옵션 존재

### Merge Commit
- 두 브랜치를 공통 부모로 하는 새로운 commit 'E'를 만듦
- A, B, C의 커밋이 그대로 main 브랜치로 병합

### Squash amd Merge
- A, B, C의 커밋을 'squash'
- 하나의 커밋으로 main 브랜치로 병합

### Rebase and Merge
- A, B, C 커밋의 base를 재설정
- 모두 새로운 커밋으로 변경
- commit hash가 변경됨
- 무수한 충돌을 경험할 수 있으니 사용에 주의

#### Commit Id
- commit의 실별을 위해 사용하는 40자 길이의 16진수
- 중복 확률은 2의 80제곱 분의 1
- SHA-1 해시 함수를 사용
  
https://github.com/honghong0303/2024-1-Beginner-Study/pull/2