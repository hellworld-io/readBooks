# Clean Code

## Chapter 4 주석

* 프로그래밍 언어를 조율해 의도를 표현할 능력이 있다면 주석은 거의 필요하지 않다.
* 코드로 의도를 표현하지 못해, 실패를 만회하기 위해 주석을 사용한다.
* 주석으로 의도를 표현하기 보다 코드로 의도를 표현하는 방법을 연구하라.
* 주석은 오래될수록 코드에서 멀어진다.
* 오래될수록 완전히 틀려질수도 있다.
* 프로그래머들이 주석을 유지보수하기란 현실적으로 불가능하다.
* 코드는 변화하고 진화하지만 주석은 언제나 코드를 따라가지 않는다.
* 부정확한 주석은 아예 없는거 보다 훨씬 나쁘다.
* 부정확한 주석은 독자를 현혹하고 오도한다.
* 부정확한 주석은 결코 이뤄지지 않을 기대를 심어준다.
* 부정확한 주석은 더 이상 지킬 필요가 없는 규칙이나 지켜서는 안되는 규칙을 명시한다.
* 코드만이 자기하 하는 일을 진실하게 말한다.

4-1. 주석은 나쁜 코드를 보완하지 못한다.
* 코드에 주석을 추가하는 일반적인 이유는 코드 품질이 나쁘기 때문이다.

4-2. 코드로 의도를 표현하라.
* 주석으로 달려는 설명을 함수로 만들어 표현하라.

4-3 좋은 주석
* 정말로 우수한 주석은 달지 않을 방법을 찾아낸 주석
* 법적인 주석
* 정보를 제공하는 주석
	* 주석으로 기본정보를 제공하면 편리함.
* 의도를 설명하는 주석
* 의미를 명료하게 밝히는 주석
	* 애매한 인수나 반환 값을 그 의미를 읽기 좋게 표현하면 이해하기 쉬워진다.
    * 주석이 올바른지 검증하기는 쉽지 않다.
* 결과를 경고하는 주석
* TODO 주석
	* 프로그래머가 필요하다 여기지만 당장 구현하기 어려운 업무를 기술
* 중요성을 강조하는 주석.

* 공개 API에서 Javadocs.

4-4. 나쁜 주석.

* 대다수의 주석이 나쁜주석.
* 주절거리는 주석
	* 특별한 이유없이 의무감으로, 마지못해 다는 주석은 시간낭비이다.
	* 이해가 안되 다른 모듈까지 뒤져야 하는 주석은 독자와 제대로 소통하지 못하는 주석이다.
* 같은 이야기를 중복하는 주석
* 오해할 여지가 있는 주석
* 의무적으로 다는 주석
* 이력을 기록하는 주석
* 있으나 마나한 주석
* 무서운 잡음
* 함수나 변수로 표현할 수 있다면 주석을 달지 마라.
* 위치를 표시하는 주석
* 닫는 괄호에 다는 주석
* 공로를 돌리거나 저자를 표시하는 주석
* 주석으로 처리한 코드
	* 주석으로 처리된 코드는 다른사람이 지우기를 주저한다.
	* 이유가 있어서 남겨놓았으리라고, 중요하니까 지우면 안된다고 생각한다.
	* 쓸모없는 코드가 쌓여간다.
* HTML 주석
* 전역정보
	* 주석을 달아야 한다면 근처에 있는 코드만 기술하라.
	* 코드 일부에 주석을 달면서 시스템 전반적인 정보를 기술하지 마라.
* 너무 많은 정보
* 모호한 관계
	* 주석과 주석이 설명하는 코드는 둘 사이 관계가 명백해야 한다.
* 함수 헤더
* 비공개 코드의 Javadocs