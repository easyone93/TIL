
# git 기초

## git 의 개념과 학습 이유
형상 관리 도구 또는 버전 관리 시스템으로 소스코드를 효율적으로 관리할 수 있도록 해주며 여러 명의 사용자들 간에 해당 파일들의 작업을 조율하기 위한 분산 버전 관리 시스템

### vcs(Version Control System)
변경되는 파일의 이력을 효율적으로 관리할 수 있게 하는 시스템으로 파일의 이력을 기록하여 문제 발생시 특정 시점으로 파일을 복원 할 수 있는 기능 제공

### working Directory

### satge

### commit

## git 사용법

|명령어|예시|설명|
|-|-|-|
|init|git init| .git 생성 .git으로 버전 관리, 리포지토리 생성|
|add|git add .| stage에 변경 사항을 등록|
|commit|git commit -m 'message'| stage에 등록된 변경 내용을 |
|status|git status| 저장소의 상태 확인|
|log|git log| 커밋 상황 확인|
|restore|git restore --staged| 저장된 이전의 상황으로 되돌림|


             restore

working directory -> stage -> commits -> working directory

                add    commit





git config --global usser.name "name"
git config --global user.email "email@com"