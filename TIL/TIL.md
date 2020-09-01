# TIL



## SCP

- 파일 전달하기
  - scp [파일] [상대주소:폴더경로]
  - scp ./file.ext user@192.168.149.128:/temp
- 파일 가져오기
  - scp [상대주소:파일주소] [저장할 폴더]
  - scp user@192.168.148.128:/tmp/file.txt ~/test[복사대상(현재 pc경로)]
- scp -r : 폴더 재귀적으로 가져오기
- cp 명령어와 크게 상관없음



## SSH 키 생성

- ssh-keygen
  - ~/.ssh 폴더에 파일 생성
    - id_rsa
    - id_rsa.pub
  - cat id_rsa.pub 공개키 복사
- 깃허브 SSH 등록(id_rsa_pub 등록)
  - private 리파지토리 복사 시 SSH 주소 복사