### 파일 삭제

#### 리눅스 명령 파일 삭제
-**`rm [file]`** : WD 삭제

#### 깃 명령 파일 삭제
-**`git rm [file]`** : WD, SA삭제
(Tracked 상태 -> Untracked 상태)

-**`git rm –-cached [file]`** : SA삭제

SA, WD에 파일X일 경우 **`git status -s`**시 D(초록) file
SA에만 파일이 없으면 ??(빨강) file(Untracked 의미)

---

### 파일 복원
WD, SA, GR 모두 다른 상태 가정
-**`git restore f`** : SA -> WD
-**`git restore --staged f`** : GR -> SA
-**`git restore --source=HEAD f`** : GR -> WD
-**`git restore --source=HEAD --staged --worktree f`** : GR -> SA, WD
