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

2. **저장소 동기화**
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

### 파일 관리 명령어
- **`touch [파일명]`** : 빈 파일을 생성
- **`echo [내용] > [파일명]`** : 파일에 내용을 새로 저장
- **`echo [내용] >> [파일명]`** : 파일에 내용을 추가
- **`cat [파일명]`** : 파일 내용을 화면에 출력
- **`cp [파일1] [파일2]`** : 파일1을 파일2로 복사
- **`mv [파일1] [파일2]`** : 파일1을 파일2로 이름 변경
- **`rm [파일명]`** : 파일을 삭제

---

### 변경사항 관리
- **`git status`** : 변경 상태 확인
- **`git add [파일명]`** : 변경된 파일 스테이징
- **`git commit -m [메세지]`** : 커밋 저장

---

### Git 로그 및 이력 확인
- **`git log`** : 기본 로그 확인  
- **`git log --oneline`** : 한 줄 로그 확인  
- **`git log --graph`** : 그래프 형태로 확인 
- **`git checkout HEAD~1`** : 이전 커밋으로 이동  
- **`git checkout main`** : 최신 상태로 복귀  

---
