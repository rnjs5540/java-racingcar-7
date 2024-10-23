# 우테코 7기 프리코스 2주차: <br>java-racingcar-precourse

## 1. 학습 목표

- 여러 역할을 수행하는 큰 함수를 단일 역할을 수행하는 작은 함수로 분리한다.
- 테스트 도구를 사용하는 방법을 배우고 프로그램이 제대로 작동하는지 테스트한다.
- 1주 차 공통 피드백을 최대한 반영한다.

---

## 2. 기능 요구사항
초간단 자동차 경주 게임을 구현한다.

- 주어진 횟수 동안 n대의 자동차는 전진 또는 멈출 수 있다.
- 각 자동차에 이름을 부여할 수 있다. 전진하는 자동차를 출력할 때 자동차 이름을 같이 출력한다.
- 자동차 이름은 쉼표(,)를 기준으로 구분하며 이름은 5자 이하만 가능하다.
- 사용자는 몇 번의 이동을 할 것인지를 입력할 수 있어야 한다.
- 전진하는 조건은 0에서 9 사이에서 무작위 값을 구한 후 무작위 값이 4 이상일 경우이다.
- 자동차 경주 게임을 완료한 후 누가 우승했는지를 알려준다. 우승자는 한 명 이상일 수 있다.
- 우승자가 여러 명일 경우 쉼표(,)를 이용하여 구분한다.
- 사용자가 잘못된 값을 입력할 경우 IllegalArgumentException을 발생시킨 후 애플리케이션은 종료되어야 한다.

---


## 구현할 기능 목록

### 1. 자동차 등록
- 자동차의 이름을 입력받는다.
- 쉼표(`,`)를 기준으로 파싱한다.

### 2. 이동 관련 기능
- 이동횟수를 입력받는다.
- 무작위로 전진하는 기능을 구현한다.

### 3. 차수별 실행 결과 출력 기능
- 각 자동차의 이동결과를 출력한다.

### 3. 승자 발표 기능
- 우승자를 출력한다. 여러 명일 경우 쉼표(`,`)로 구분한다.

---

## 주의할 사항
- 쉼표(`","`) 외에 공백문자(`" "`)가 올 시 어떻게 처리 할 지
  - 쉼표 전후의 공백문자는 제거해주기로 결정
