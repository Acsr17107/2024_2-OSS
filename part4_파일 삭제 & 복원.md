### 파일 삭제

#### 리눅스 명령 파일 삭제
-**`rm [file]`** : 작업 디렉토리 file 삭제

#### 깃 명령 파일 삭제
-**`git rm [file]`** : 작업 디렉토리와 스테이징 영역에서 모두 file 삭제
(Tracked 상태 -> Untracked 상태)

-**`git rm –-cached [file]`** : 스테이징 영역에서 file 삭제

SA, WD에 파일X일 경우 **`git status -s`**시 D(초록) file
SA에만 파일이 없으면 ??(빨강) file(Untracked 의미)

---
