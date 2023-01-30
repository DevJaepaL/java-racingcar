# 중요사항 정리

> 중요 포인트 
> 1. 함수를 최대한 쪼개는 것. (**함수 내부 길이가 15줄 이상이면 안된다 !**)
> 2. else 예약어 사용 금지 ❌
>   + if 조건절에서 `return` 값 주는 형식으로 구현.
>   + 또한 `switch / case` 도 사용 금지 ❌
> 3. **자바 코드 컨벤션** 룰 지키면서 프로그래밍
> 4. `indent depth`를 3이 넘지 않도록 구현.
>   + 즉, 삼중 이상 중첩하여 예약어 사용 금지.
> 5. 입력 값은 기본 API(`Random` , `Scanner`) 대신, `camp.nextstep.edu.missionutils` 에서 제공하는 API를 이용해야한다.
> 6. `Git`의 커밋 단위는 앞 단계에서 `README.md` 파일에 정리한 기능 목록 단위로 추가한다.
>    + [AngularJS Commit MessageConventions](https://docs.google.com/document/d/1QrDFcIiPjSLDn3EL15IJygNPiHORgU1_OOAqWjiDU5Y/edit#heading=h.uyo6cb12dt6w) 를 참고해 `Commit Log` 를 남긴다.

## 구현할 기능 목록

1. **자동차의 전진 , 멈춤** 기능
   + 전진 조건 : **0 - 9의 숫자 중 무작위 값을 구한 뒤 4 이상일 경우 전진**
   + **총 전진 횟수는 사용자가 입력하여 조절 가능**하다.
   + 주어진 횟수동안 자동차의 전진 , 멈춤을 정할 수 있다.
2. **자동차 이름 구분** 기능
   + 자동차 이름을 `,` 를 기준으로 하여 `Car` 객체 생성.

3. **자동차 경주 완료 후 우승** 기능
   + 게임 완료 후 누가 우승했는 지를 알려준다. 우승자는 여러 명일 수 있다.
   + 우승자가 여러 명일 경우 공동우승을 선정. 
     + 공동우승자 출력은 `,`를 이용하여 구분한다.

4. **예외처리(`IllegalArgumentException`)** 기능
   + 사용자가 잘못된 값을 입력한 경우 `IllegalArgumentException` 예외를 일으켜 **"[ERROR]"**로 시작하는 **에러 메세지 출력 후 그 부분부터 다시 입력.**
