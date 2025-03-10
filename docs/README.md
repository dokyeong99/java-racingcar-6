# 🚗🚙 미션  - 자동차 경주 
## 📄 구현 기능 목록 
- 유저에게 자동차 이름을 ","을 간격으로 입력받는다.
- 유저에게 진행 라운드 수를 입력받는다.
- 유저에게 입력받은 수만큼 라운드를 진행한다.
- 결과를 출력한다.
  
## 📜 기능 요구사항
- 유저에게 입력받은 자동차의 이름의 최대 길이는 5자이다.
- 사용자의 입력이 잘못된 경우 IllegalArgumentException 에러를 발생시킨다.
- 전진하는 조건은 0에서 9 사이에서 무작위 값을 구한 후 무작위 값이 4 이상일 경우이다.
- 우승자가 여러 명일 경우 쉼표(,)를 이용하여 구분한다.

## 💻 프로그래밍 요구사항
- indent depth는 2까지만 허용된다.
- 3항 연산자를 쓰지 않는다
- 함수 또는 메서드는 한 가지 일만 하도록 최대한 작게 만든다.
- 본인이 정리한 기능 목록이 정상 작동함을 테스트 코드로 확인한다.

## 💻 프로젝트 구조 및 기능
- RacingCarController에서 서비스 클래스를 주입받아서 게임을 실질적으로 진행한다.
- UserInputservice에서 유저로부터의 입력 및 예와사항을 처리한다.
  => 입력받은 유저의 데이터를 RacingCarEntity로 객체화하여 게임을 진행한다.
- PlayGameService에서 유저에게 입력받은 데이터를 바탕으로 게임을 진행한다.
- PrintResultService에서 게임의 결과를 출력한다.
