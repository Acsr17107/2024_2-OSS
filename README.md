# 2024년도 2학기 오픈소스 소프트웨어
## OSS 교과목 내용 (Git & GitHub) 정리

---

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
