URL: 리소스를 얻는 주소(ex: 교촌치킨 신촌점 주소)
URN: 리소스의 이름을 나타낸다(ex: 도서출판 번호)

길고 복잡한 ip주소는 외우거나 관리가 어려움
ip주소는 바뀔 수 있음----->dns 등장

www.hongik.ac.kr 를 입력->도매인 서버가 연결 시켜줌

리소스: html, css, jss파일들
리소스를 이용해 브라우저가 사이트를 그림

html: 자료(뼈대)
css: ui(살과 옷)
js: 제어 체계

git: 파일의 변경 사항을 추적하는 작업과 조율함
그래서 뭘 할 수 있는데? ->코드의 다른 버전을 만들 수 있음 ex) 분기를 나누거나 합침/ 변화를 추적함(버전을 관리하여 특정 시점으로 되돌리는 것도 가능)

파일의 4가지 상태
1.추적x
2.변경x
3.변경o
4.staged

         add               commit
작업공간------>staged area---------> local repository

add: working directory에서의 변경 내용을 staging area에 추가하기 위한 명령어
commit: 변경 사항을 local에 기록하기 위한 명령어
push: push명령어를 통해 변경 사항을 local repository에서 remote repository로 보냄

git fetch: remote repository에 최신 정보를 확인하라는 명령을 전달한다. 단 fetch는 remote repository에 변경사항이 있는지 확인만 하고, 변경된 데이터를 로컬 Git에 실제로 가져오지는 않는다.
git pull: remote repository에서 변경된 데이터 정보를 확인할 뿐만 아니라 최신 데이터를 복사하여 로컬 Git에 가져옵니다