# Git Branch

1. Git Branch 확인
  - git branch

<br>

2. Git Branch 생성
  - git branch `<branch-name>`

<br>

3. Git Branch 전환
  - git checkout `<branch-name>`
  - git switch `<branch-name>`

<br>

4. 브랜치 생성 및 전환 한번에 처리하기
  - git checkout -b `<branch-name>`
  - git switch -c `<branch-name>`

<br>

5. Git Branch 병합
  - git merge `<branch-name>`

<br>

6. Git Branch 삭제
  - git branch -d `<branch-name>`
    - 로컬에서 특정 브랜치를 삭제합니다. 병합되지 않은 변경 사항이 있는 경우 삭제를 거부합니다.
  - git branch -D `<branch-name>`
    - 강제로 브랜치를 삭제합니다. 병합되지 않은 변경 사항이 있어도 삭제됩니다.

<br>

7. 리모트(원격저장소) 브랜치 보기
  - git branch -r