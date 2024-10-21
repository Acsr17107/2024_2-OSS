## 2024년도 2학기 오픈소스 소프트웨어
### OSS 교과목 내용(Git & GitHub)의 정리(개인과제 저장소)

#### Git 명령어 기초
- `git --version` : 버전확인
- `git config --list` : 설정확인

#### Git의 핵심 명령어
- `git clone` : 원격 저장소에서 로컬 저장소로 프로젝트를 복제
- `git add` : 변경된 파일을 스테이징 영역에 추가
- `git commit` : 스테이징 영역에 있는 변경 사항을 기록하고, 변경 이력을 저장
- `git push` : 로컬 저장소에서 원격 저장소로 변경 사항을 업로드
- `git pull` : 원격 저장소의 최신 변경 사항을 로컬로 가져옴

#### 주요 6가지 설정
- `git config --global user.name _` : 사용자 이름
- `git config --global user.email _` : 사용자 메일
- `git config --global core.autocrlf true` : 줄바꿈 자동변환
- `git config --global core.safecrlf false` : 줄바꿈 안전 설정
- `git config --global core.editor 'code --wait'` : 기본 편집기 설정
- `git config --global init.defaultBranch main` : 기본 브랜치 이름

#### 설정범위
- `--global` : 현재 사용자에게 전역적으로 설정
- `--local` : 현재 저장소에만 설정

#### 저장소 생성
- `git init _` : 저장소 생성

#### 리눅스 기본 명령어
- `pwd` : 현재 폴더 표시
- `cd` : 폴더 이동
- `ls` : 파일 목록 조회(-l: 상세 정보, -a: 숨김 파일, -al: 앞에 두 개 조합)
- ``
- ``
- ``
