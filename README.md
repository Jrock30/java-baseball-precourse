# 숫자 야구 게임
## 진행 방법
* 숫자 야구 게임 요구사항을 파악한다.
* 요구사항에 대한 구현을 완료한 후 자신의 github 아이디에 해당하는 브랜치에 Pull Request(이하 PR)를 통해 과제를 제출한다.

## 과제 제출 과정
* [과제 제출 방법](https://github.com/next-step/nextstep-docs/tree/master/precourse)

- - -

## 기능 요구사항

- 기본적으로 1부터 9까지 서로 다른 수로 이루어진 3자리의 수를 맞추는 게임이다. 
- 같은 수가 같은 자리에 있으면 스트라이크, 다른 자리에 있으면 볼, 같은 수가 전혀 없으면 포볼 또는 낫싱이란 힌트를 얻고, 그 힌트를 이용해서 먼저 상대방(컴퓨터)의 수를 맞추면 승리한다.
  - [예] 상대방(컴퓨터)의 수가 425일 때, 123을 제시한 경우 : 1 스트라이크, 456을 제시한 경우 : 1 스트라이크 1볼, 789를 제시한 경우 : 낫싱
- 위 숫자 야구게임에서 상대방의 역할을 컴퓨터가 한다. 컴퓨터는 1에서 9까지 서로 다른 임의의 수 3개를 선택한다. 
  게임 플레이어는 컴퓨터가 생각하고 있는 3개의 숫자를 입력하고, 컴퓨터는 입력한 숫자에 대한 결과를 출력한다.
- 힌트를 이용하여 상대방(컴퓨터)의 수를 맞추면 승리한다.
- 게임을 종료한 후 게임을 다시 시작하거나 완전히 종료할 수 있다.

### e.g.

- 컴퓨터 의 수가 123
  > 456 를 입력한 경우 : nothing  
  > 145 를 입력한 경우 : 1 strike  
  > 134 를 입력한 경우 : 1 strike 1 ball
  > 214 를 입력한 경우 : 2 ball  
  > 123 를 입력한 경우 : 3 strike

- - -

## 프로그래밍 요구사항

- 자바 코드 컨벤션을 지킨다.
  > https://naver.github.io/hackday-conventions-java
- indent(인덴트, 들여쓰기) depth를 2가 넘지 않도록 구현한다. 1까지만 허용한다
  > 예를 들어 while문 안에 if문이 있으면 들여쓰기는 2이다.  
  > 힌트: indent(인덴트, 들여쓰기) depth를 줄이는 좋은 방법은 함수(또는 메소드)를 분리하면 된다.
- 자바 8에 추가된 stream api를 사용하지 않고 구현해야 한다. 단, 람다는 사용 가능하다.
- else 예약어를 쓰지 않는다.
  > 힌트: if 조건절에서 값을 return하는 방식으로 구현하면 else를 사용하지 않아도 된다.  
  > else를 쓰지 말라고 하니 switch/case로 구현하는 경우가 있는데 switch/case도 허용하지 않는다.
- 함수(또는 메소드)의 길이가 10라인을 넘어가지 않도록 구현한다.
  > 함수(또는 메소드)가 한 가지 일만 잘 하도록 구현한다.

- - -
### 단위 테스트

- 핵심 로직을 구현하는 코드와 UI를 담당하는 로직을 구분한다.

---

## 과제 진행 요구사항

- AngularJS Commit Message Conventions 참고해 commit log를 남긴다.
