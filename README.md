# 2024년도 2학기 오픈소스 소프트웨어
## OSS 교과목 내용 (Git & GitHub) 정리

---

### 커밋(commit)

- **`git commit -m 'A'`** : 커밋 메세지 A를 직접 입력
- **`git commit -am 'A'`** : 메세지 A를 추가와 커밋을 함께 실행

---

### 커밋 로그 이력 확인

- **`git log`** : 로그 이력 정보 표시
   - **`git log --oneline`** : 로그 이력 한 줄로 표시
   - **`git log -p`** : 로그 이력과 파일의 변화 표시

- **`git show`** : 마지막 커밋 정보 표시
   - **`git show --oneline`** : 커밋 로그 한 줄, 파일 차이 표시
   - **`git show -s`** : 파일 차이는 표시 X
   - **`git show HEAD`** : 현재 커밋 정보 표시
      - **`HEAD~, HEAD~1, HEAD^,zHEAD^1`** : 바로 전 커밋 정보 표시
      - **`HEAD~~, HEAD~2, HEAD^^, HEAD^~, HEAD~^`** : 2단계 전 커밋 정보 표시

---

### 과거 당시의 파일 내용 확인

- ```(3영역 동일한 상태일 때 가능)```
- **`git checkout HEAD~`** : HEAD 이전 커밋으로 이동
- **`git checkout -`** : 다시 checkout 이전으로 이동
- **`git checkout main`** : 다시 최신 버전으로 이동

---

### 로그 이력
- **`git status -s`**로 로그이력 조사
- 작업 디렉토리   스테이징 영역   깃 저장소
-      aaa                                  ??(빨강)
-      aaa           aaa                    A (초록)
-      aaa           aaa           aaa       표시 X

-      aaa
-      bbb                                  M (빨강)

-      aaa           aaa            aaa
-      bbb           bbb            bbb      표시 X

-      aaa           aaa            aaa
-      bbb           bbb            bbb
-      ccc                                   M (빨강)

-      aaa           aaa            aaa
-      bbb           bbb            bbb
-      ccc           ccc                     M (초록)

-      aaa           aaa            aaa
-      bbb           bbb            bbb
-      ccc           ccc                     
-      ddd                                   MM(초록 빨강)
