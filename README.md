# 2024년도 2학기 오픈소스 소프트웨어
## OSS 교과목 내용 (Git & GitHub) 정리

---

### Git 명령어 기초
- **`git --version`** : Git 버전 확인
- **`git config --list`** : Git 설정 확인

---

### Git의 핵심 명령어

1. **저장소 복제**
   - `git clone` : 원격 저장소에서 로컬로 프로젝트 복제

2. **변경사항 관리**
   - `git add` : 변경된 파일을 스테이징 영역에 추가
   - `git commit` : 스테이징된 변경사항을 기록하고 저장

3. **저장소 동기화**
   - `git push` : 로컬 변경사항을 원격 저장소로 업로드
   - `git pull` : 원격 저장소의 최신 변경사항을 로컬로 가져옴

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

### 설정 범위

- **`--global`** : 모든 저장소에 적용 (전역 설정)
- **`--local`** : 현재 저장소에만 적용 (로컬 설정)

---

### Git 저장소 생성

- `git init [폴더 이름]` : 새로운 Git 저장소 생성

---

### 리눅스 기본 명령어

- **`pwd`** : 현재 폴더 경로 표시
- **`cd [폴더 이름]`** : 특정 폴더로 이동
- **`ls`** : 현재 폴더의 파일 목록 조회
  - `ls -l` : 파일 목록과 상세 정보 표시
  - `ls -a` : 숨김 파일 포함 모든 파일 표시
  - `ls -al` : 숨김 파일과 상세 정보를 모두 표시

---

- **`touch [파일명]`** : 빈 파일을 생성합니다.
- **`echo [내용] > [파일명]`** : 파일에 내용을 새로 저장합니다.
- **`echo [내용] >> [파일명]`** : 파일에 내용을 덧붙입니다.
- 
