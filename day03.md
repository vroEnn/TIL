#### 상태 확인
- git log --oneline --all --graph
#### 개별 커밋 비교
- git diff 해쉬값 해쉬값 


#### git bash에서 
- git config --global core.editor "code --wait
- git config --global --list

#### 수정>저장>add>commit>push
```
touch README.md
파일 수정 : 마스터에서 작성 1
저장
git add . 
git commit -m "first commit-master"


(master 브랜치에서)
git branch test
git switch test

(test 브랜치에서)
파일 수정 : 테스트에서 작성 1
저장
git add .
git commit -m "first commit-test"
git switch master
(master 브랜치로 복귀)
git switch master
```
### 안녕 