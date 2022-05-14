# 로또
## 진행 방법
* 로또 요구사항을 파악한다.
* 요구사항에 대한 구현을 완료한 후 자신의 github 아이디에 해당하는 브랜치에 Pull Request(이하 PR)를 통해 코드 리뷰 요청을 한다.
* 코드 리뷰 피드백에 대한 개선 작업을 하고 다시 PUSH한다.
* 모든 피드백을 완료하면 다음 단계를 도전하고 앞의 과정을 반복한다.

## 온라인 코드 리뷰 과정
* [텍스트와 이미지로 살펴보는 온라인 코드 리뷰 과정](https://github.com/next-step/nextstep-docs/tree/master/codereview)

## step2 문자열 덧셈 계산기

### 기능목록
* 기본 구분자로 숫자를 구분한다
* 빈문자열 또는 null인 경우에는 0을 반환
* 숫자 하나만 입력되면 해당 숫자 반환
* 커스텀 구분자로 숫자를 구분하는 기능
* 입력받은 값에 숫자 이외에 값 또는 음수를 전달하는 경우 validate
* 숫자리스트를 모두 더하여 계산

## step3 로또(자동)

### 기능목록
* 로또는 1000원 단위로만 구매할 수 있다
* 로또 구입금액으로 로또 구매개수를 구할 수 있다
* 로또 번호 6개를 생성할 수 있다
* 당첨번호를 입력받을 수 있다
* 당첨번호를 통해 로또번호의 일치 개수를 구할 수 있다
* 여러개의 로또결과를 통계낼 수 있다
* 수익율을 계산할 수 있다