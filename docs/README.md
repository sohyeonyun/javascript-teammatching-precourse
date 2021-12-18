# [기능 목록]

## 1) 공통

- [-] 크루 관리 탭을 클릭 시 메뉴가 나타난다.
- [-] 팀 매칭 관리 탭을 클릭 시 메뉴가 나타난다.
- [-] 다른 탭으로 이동했다 돌아와도 기존 탭의 상태가 유지되어야 한다.
- [-] localStorage를 이용하여, 새로고침하더라도 가장 최근에 작업한 정보들을 불러올 수 있도록 한다.

## 2) 크루 관리 기능 탭

- [-] 사용자가 선택한 코스(FE, BE)를 입력받는다.
- [-] 사용자가 입력한 크루 이름의 유효성을 확인한다.
  - [-] 동일한 이름의 크루는 추가할 수 없다.
  - [-] 크루 이름은 최대 5글자까지 가능하다.
- [-] 크루 이름 입력 시, 크루 목록을 테이블로 보여준다.
  - [-] 크루 table의 첫번째 열에는 index를 넣어 순서를 표시한다. index는 '1'부터 시작한다.
- [-] 코스별로 크루를 삭제할 수 있다.
- [-] 삭제할 때는 confirm을 사용하여, 사용자가 한번 더 확인할 수 있게 한다.

## 3) 팀 매칭 관리 기능

- [-] 팀 매칭을 관리한 코스, 미션을 입력 받을 체크리스트를 만든다.
- [-] 확인 버튼 클릭 시, 코스, 미션을 입력받는다.
- [-] 팀당 인원 수를 입력 받는다. -[-] 자연수여야 한다.
- [-] 팀 매칭 시 1팀당 인원 수 에 입력한 값 보다 더 적은 수의 크루들로 구성된 팀이 없어야 한다. 남은 인원은 앞 팀부터 순서대로 배정한다.
- [-] 팀매칭 결과를 보여준다.
  - [-] 팀 매칭 결과는 쉼표로 구분한다.
- [-] 재매칭 버튼 클릭 시, 팀은 재매칭할 수 있다.