# [2주차] 미션 - 숫자 야구
## 기능 목록
- [ ] 게임 시작 문구를 출력한다.
- [ ] 상대방(컴퓨터)의 수를 생성한다.
- [ ] 사용자가 수를 입력한다.
    - [ ] 입력 값이 3개가 아니면 에러가 발생한다. - `IllegalArgumentException`
    - [ ] 숫자가 아닌 값이 입력되면 에러가 발생한다. - `IllegalArgumentException`
    - [ ] 입력 값이 범위(1~9)를 벗어나면 에러가 발생한다. - `IllegalArgumentException`
    - [ ] 서로 다른 3개의 수로 이루어지지 않았으면 에러가 발생한다. - `IllegalArgumentException`
- [ ] 상대방(컴퓨터)의 수와 사용자의 수를 비교한다.
- [ ] 결과를 출력한다.
  - [ ] 출력할 결과가 `3스트라이크`이면 `3개의 숫자를 모두 맞히셨습니다! 게임 종료`를 함께 출력한다.
  - [ ] 출력할 결과가 `3스트라이크`이면 게임 재진행 여부를 입력받는다.
    - [ ] 입력 값이 1개가 아니면 에러가 발생한다. - `IllegalArgumentException`
    - [ ] 숫자가 아닌 값이 입력되면 에러가 발생한다. - `IllegalArgumentException`
    - [ ] 입력 값이 범위(1~2)를 벗어나면 에러가 발생한다. - `IllegalArgumentException`
  