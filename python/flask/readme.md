# flask 활용하기

- 본 폴더는 멀티캠퍼스에서 2월 23일부터 28일까지 진행한 수업을 기반으로 flask의 기초 사용법을 다룬다.



## flask_intro

- 본 프로젝트에서는 flask의 기본 활용법을 익혔다.
- 라우터 기능을 통해 url 경로를 지정하는 것이 주된 목표였다.
- flask의 라우팅 기능은 eclipse에서 servlet의 url 경로를 web.xml으로 맵핑하는 과정과 상당 부분 유사했다.



## telegram

- 텔레그램을 이용한 챗봇 구현 기능 코드이다.
- 실제로는 c9.io 서버를 이용하였고, 추후 heroku로 배포하기도 했다.
- 수업을 마친 뒤에도 출결 기록과 같은 몇 가지 기능들을 추가하였다.



## heroku

- heroku 사이트와 github를 연동하여 가상의 서버를 배정받는 방법을 익혔다.
- 그러나 heroku에서 위 출결 기록 기능을 구현하려고 했을 때 동적으로 내용이 수정되는 txt 파일을 반영하지 못하여 실패한 내역이 있다.
- 이 문제는 추후 heroku db 관리 api을 이용하여 해결할 수 있을 것으로 보인다.