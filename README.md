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
   - **`git show [HEAD]`** : 지정한 HEAD 커밋 정보 표시

---

