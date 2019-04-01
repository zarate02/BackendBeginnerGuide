# BackendBeginnerGuide 

## 서론

백앤드 서버개발자를 시작하기 위한 사람에게 공부방향을 제시하기위해 작성하게 되었다.<br>
다른 분야와 마찬가지로 백앤드서버는 꽤나 많은 부분에대한 학습이 동시에 진행되어야한다.<br>
최소 통신, 운영체제, 자료구조는 배경지식으로 가지고 있어야되고 학습을 위한 C, 실전을 위한 JAVA를 우선적으로 학습하길 추천한다.<br>


## 1. 왜 SI 백앤드서버는 자바로 개발할까?

개인적으로 가장 좋아하는 언어는 C언어다<br>
하지만 실전에는 왠만하면 자바를 쓰는 편이다.<br>
자바보다 젊은 언어인 Go, 파이썬, 루비 도있고 프로그래밍의 정점이라고 불리는 C++도 있지만 왜 JAVA를 주무기로 사용할까?<br>

### 1) 당신이 알고있는 모든 운영체제에서 동작할 것이다

자바는 호환성이 좋은 언어이다.<br>
애초에 자바가 탄생한것이 이기종의 장비에서 같은 소스로 같은 컴파일된 결과물을 실행하기위한 목적이기에 더욱더 그렇다.<br>
최신언어들은 대부분이 호환성이 좋지만 자바만큼 오랜기간 검증되었고, 사용자가 많으면서 동시에 이정도의 호환성을 자랑하는 언어는 많지않다.<br>
특히 어떤 OS에 설치해야될지 알수없는 상태가 빈번한 SI개발자입장에서는 좋은 선택지가 된다.<br>

### 2) 백앤드에 최적화되어있는 라이브러리를 가장 풍부하게 제공

스프링이라는 강력한 프레임워크를 등에업고 자바는 가장 강력한 백앤드 개발언어로 부상했다.<br>
파이썬진영에서 장고를 루비진영에서 루비온레일즈로 대항했지만 <br>
가장 사용자가 많고, 가장 풍부한 백앤드 라이브러리를 보유한 언어가 자바임에는 누구도 부정하기 힘들다.<br>

### 3) 참고자료가 풍부하다

교육용언어로 가장 적합한건 C라고 생각하고, 요즘 학교나 학원에서는 파이썬을 많이 가르친다고 하지만<br>
실전용으로 백앤드서버 개발에 사용할 수 있는 언어중에 가장 빨리 습득할 수 있는 언어는 자바라고 생각한다.<br>
유투브에 JAVA관련 자료만 찾아도 방대한 자료가 나오며 스택오버플로우에서도 가장 사랑받는 언어중에 하나가 자바이다.<br>



## 2. 하지만 처음이라면 C부터 

앞에서 자바의 장점을 말했지만 언어를 처음배우는 사람이라면 자바를 먼저 배우는걸 추천하지 않는다.<br>
그 이유는 딱 하나다, 자바는 하지못한것을 C는 할수있다, 바로 메모리 관리이다.<br>
언어의 시작은 항상 메모리를 자동관리 해주지않는 언어로 시작하는 것이 베스트라고 생각한다.<br>
이 부분을 건너뛰고 간다면 두고두고 발목을 잡힐 위험이 있다, 자바를 먼저하면 컴퓨터가 메모리를 어떻게 관리하는가에대한 것을 놓치기 쉽다.<br>

C 추천강의 : https://www.youtube.com/watch?v=I5jmg6uUTbQ&list=PLXvgR_grOs1AQuQ-5mWbx0zdG0betdeoL



## 3. 왜 통신, OS, 자료구조를 공부해야되는가?

실제 업무에서는 프로그래밍 언어를 잘아는 것만으로 해결되지않는다.<br>
서버프로그래밍을 만든다면 통신에대해 알아야될 것이며 그래야 부하관리, 성능향상, 프로토콜구축 등을 해낼 수 있으며<br>
좀더 깊이들어간다면 OS와 밀접한 연관이 있다.<br>
또 자료구조는 전통적인 모델도 중요하지만 자신이 어떤 업무를 하는가에 따라 DB, NoSql, MQ 부터 하둡과 같은 빅데이터를 위한 데이터저장법을 학습해 나아가야 보다 자신이 할수있는 영역을 넓힐수 있다는건 당연한 이야기다.<br>

OS 추천강의 : https://www.youtube.com/watch?v=mcS4n34wBcY&list=PLZHI9CmwUWQoljS34piBQhqrPp4cQfnsz
통신 추천강의 : http://www.kocw.or.kr/home/search/kemView.do?kemId=1260383
DB 추천자료 : http://www.gurubee.net/roadmap/oracle
