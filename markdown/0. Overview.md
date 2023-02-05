# 1. 개요
이 튜토리얼에서는 Flaskr이라는 기본적인 블로그 애플리케이션을 만드는 과정을 안내한다.
- 사용자는 회원 등록, 로그인, 게시물 작성하고 자신의 게시물을 편집하거나 삭제할 수 있다.
- 또한 애플리케이션을 패키지화하고 다른 컴퓨터에 설치할 수 있다.
<br><br/>
![homepage](./image/0.%20overview_1.png)
<br><br/>

# 2. 대상과 범위
이 튜토리얼은 좋은 출발점을 제공하지만, 플라스크의 모든 기능을 다루지는 않는다.
- 파이썬에 익숙한 사람을 대상으로 하므로, [파이썬 공식 튜토리얼](https://docs.python.org/3/tutorial/index.html)을 참고하면 좋다.
- 플라스크의 기능에 대해서는 [Quicstart](https://flask.palletsprojects.com/en/2.2.x/quickstart/)에 설명되어 있다.
<br><br/>
![login](./image/0.%20overview_2.png)
<br><br/>

# 3. 플라스크의 유연성
플라스크는 유연(flexible)하다.
- 특정 프로젝트나 코드 레이아웃을 사용할 필요가 없다.
- 하지만 처음 시작할 때는 체계적인(structured) 접근이 필요하다.
- 이 튜토리얼에서는 신입 개발자들이 겪는 어려움을 피하기 위해 기존의 표준안(boilerplate)을 사용한다.
- 플라스크에 익숙해지면 이 구조에서 벗어나서 플라스크의 유연성을 최대한 활용할 수 있다.
<br><br/>
![blog](./image/0.%20overview_3.png)


