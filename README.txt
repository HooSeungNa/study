<도커>

1. 도커 설치(docker desktop)
2. 도커 이미지 ubuntu 받기 
docker search ubuntu 
docker pull ubuntu
docker create -it --name 원하는 이름 
docker exec -it 원하는 이름 bash
3. docker run -v `마운트 할 경로` --name [원하는이름] bash

<git>

1. git clone [git 주소]
2. 토큰 발급 (repo 권한 체크) -> pw 대신 쓰임
git config credential.helper store하고 커밋할때 한번 입력하면, 인증없이 사용가능
3. git cofing username, password, email 등록

<vscode>
1. extension설치 (vim, container, cpplint, prettier formatter)
2. remote 접속 누르고 컨테이너 선택

<ubuntu>
<vim 설치>
1. apt-get update
2. apt-get install vim

<한글 적용 가능하게 설정>
3. apt-get -y install language-pack-ko
4. locale-gen ko_KR.UTF-8
5. dpkg-reconfigure locales
6. Locales to be generated: 290
7. Default locale for the system environment: 3
8. export LANGUAGE=ko_KR.UTF-8
9. export LANG=ko_KR.UTF-8
