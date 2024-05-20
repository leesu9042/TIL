# TIL

## 브랜치 정의
1. A branch in Git is simply a lightweight movable pointer to one of these commits.
참고 https://git-scm.com/book/en/v2/Git-Branching-Branches-in-a-Nutshell

## 브랜치 합치기
-이슈에 해당하는 작업을 수행할 떄 ,별도의 브랜치를 만들고 작업하다
-작업이 끝난 후에는, PULL REQUEST사용해 내가 작업한 브랜치로 병합시켜야한다('main','development','devel' )로 병합시켜야한다

###명령어
-'get merge'
-주의할점 'A'브랜치를 'B'브랜치로 합치려고 할 때는 A 브랜치를 체크아웃 한 사앹에서 'git merge B'를 입력한다