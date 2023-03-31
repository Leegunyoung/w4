# w4

## Docker(oss Lecture 4th Week)

### docker 1

#### docker container

##### 도커 데몬 실행(root 권한 필요)

#####  - 아래 명령으로 서비스 실행
#####  sudo service docker start

#####  - 실행 확인
#####  ps -ef|grep dockerd

#####  - 컨테이너 실행 테스트
#####  sudo docker run hello-world

#####  사용자 그룹 추가
#####  • 확인
#####  id
#####  • 그룹 추가
#####  sudo usermod -aG docker <user id>
#####  • 확인
#####  터미널 재 로그인
#####  id


