# Git server

- 깃 서버 구축



### gitLab 구축

- 1) 필요 프로그램
  - sudo apt-get install curl openssh-server ca-certificates postfix
- 2) 리파지토리 추가
  - curl -sS https://packages.gitlab.com/install/repositories/gitlab/gitlab-ce/script.deb.sh | sudo bash
  - sudo curl -sS https://packages.gitlab.com/install/repositories/gitlab/raspberry-pi2/script.deb.sh | sudo bash
- 3) 저장소 목록 업데이트
  - apt-get update