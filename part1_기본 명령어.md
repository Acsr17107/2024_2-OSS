### Git 명령어 기초
- **`git --version`** : Git 버전 확인
- **`git config --list`** : Git 설정 확인

---

### 깃 설정 명령구조
- **`git config --설정범위 설정변수 설정값`**

#### 설정범위
- **`--system`** : 모든 사용자
- **`--global`** : 모든 저장소에 적용 (전역 설정)
- **`--local`** : 현재 저장소에만 적용 (로컬 설정)

---

### 주요 설정 명령어

1. **사용자 정보**
   - `git config --global user.name "사용자 이름"` : 사용자 이름 설정
   - `git config --global user.email "이메일 주소"` : 사용자 이메일 설정

2. **줄바꿈 설정**
   - `git config --global core.autocrlf true` : 자동 줄바꿈 변환
   - `git config --global core.safecrlf false` : 줄바꿈 안전 설정

3. **편집기와 기본 브랜치 설정**
   - `git config --global core.editor 'code --wait'` : 기본 편집기 설정
   - `git config --global init.defaultBranch main` : 기본 브랜치 이름 설정

---

### 리눅스 기본 명령어
- **`pwd`** : 현재 폴더 표시
- **`cd Directory1`** : Directory1 폴더로 이동
- **`ls`** : 현재 폴더의 파일 목록 조회
   - `ls -a` : 숨김 파일 표시
   - `ls -l` : 파일 상세 정보 표시
   - `ls -al` : 숨김 파일과 상세 정보 모두 표시
 
---

### 파일 관리 명령어
- **`touch f`** : 파일 f를 생성
- **`echo A > f`** : 파일 f에 내용 A를 새로 저장
- **`echo B >> f`** : 파일 f에 내용 B를 추가
- **`cat f`** : 파일 f 내용을 화면에 출력
- **`cp f1 f2`** : 파일 f1을 파일 f2로 복사
- **`mv old_file new_file`** : 파일 old_file을 파일 new_file로 이름 변경
- **`rm f1`** : 파일 f1를 삭제
   - `rm -r f1` : 디렉토리 내부 모든 내용 삭제
   - `rm -f f1` : 강제로 삭제
   - `rm -rf f1` : 강제로 모든 내용 삭제

---
