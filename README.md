# git-practice


README 파일은 저장소에 대한 설명을 적는 곳입니다.

## TIL

### 오늘 배운 내용
# Git

깃의 3가지 영역(Working Directory, Staging Area, Repository)

[Working Directory]  -----( git add )----->  [Staging Area]  -----( git commit )----->  [Repository]
(작업 책상 / 수정)                          (택배 상자 / 대기)                         (물류 창고 / 저장 완료)

1. Working Directory
    - VS Code나 인텔리제이 같은 에디터로 코드를 직접 타이핑하고, 파일을 새로 만들거나 수정하고 있는 **실제 컴퓨터 안의 폴더 그 자체**
2. Staging Area
    - 저장소(Repository)에 최종 기록을 남기기 전에, **"이번에 이 파일들을 묶어서 저장할 거야" 하고 찜해두는 임시 대기 장소**
3. Repository
    - Staging Area에 쌓아둔 파일들을 모아 하나의 버전으로 안전하게 저장한 **최종 데이터베이스**입니다. 깃이 관리하는 (.git 폴더 안의) 진짜 저장소

~: 홈 디렉토리

전역 이름 설정

: git config —global [user.name](http://user.name) “사용할 이름”

전역 이메일 설정

: git config —global [user.](http://user.name)email “사용할 이메일”

git 브렌치 만들기

: git switch -c ‘만들 브렌치 이름’

git 브렌치 바꾸기

: git switch ‘브랜치명’

git diff

: git에서 변화된 사항 확인


### 오늘 정리할 내용
- git에는 3가지 영역이 있다.
- Working Directory, Staging Area, Repository
- git 브렌치 만들기 : git switch -c "만들 브렌치 이름"
- git 브렌치 바꾸기 : git switch "브랜치명"
- 작업하거나 수정한 내용 확인 : git diff
