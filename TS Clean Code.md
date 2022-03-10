# ✔ TS Clean Code 



- 클래스/타입/객체의 이름에 의미가 있다면, 변수 이름에서 반복하지 X



- 함수는 한가지 일만 할 것



- 함수 매개변수로 플래그를 사용하지 말 것



- 함수 인자는 최대한 2개 이하로



- 호출하는 함수를 호출당하는 함수 바로 위에 위치 시키기



- 명령형보다 함수형 프로그래밍



- 부정 조건문 피하기



- ts alias 사용해서 import의 긴 상대경로를 깔끔하게
ex)`import { UserService } from '@services/UserService';`
`tsconfig.json`의 path와 baseUrl로 적용가능



- `readonly` 필요한 곳에 사용



- `type` vs `interface`
  - 합집합 또는 교집합이 필요할 때 `type`을 사용
  - extends 또는 implements가 필요할 때 `interface`를 사용



- 메서드 체이닝 사용



- `async/await` 사용



- `getter/setter` 사용



- catch절에서 에러처리 비우지 말것  에러가 발생했을때에 대한 계획이나 장치 마련

  

- Pascal Case

  - 클래스, 인터페이스, 타입, 네임스페이스

- Camel Case

  - 변수, 함수, 클래스멤버이름

- const는 대문자



- 조건문 캡슐화 (= if 조건문에 들어가는 코드를 함수화)



- 테스트의 이름은 테스트의 의도가 드러나게







출처 : https://738.github.io/clean-code-typescript/ 