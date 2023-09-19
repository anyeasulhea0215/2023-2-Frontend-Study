3장 변수와 값


변수:값을 담기 위한 이름을 붙인 공간.
       컴퓨터의 메모리에 일정한 크기의 영역으로 생성.

변수 선언: 
  var sum:


*자바스크립트는 변수의 종류가 없음.

변수 선언 생략 가능(var 생략):

ex) x = 2;
console.log(x); //->2



동적 타입 언어(변수):
숫자,문자열 등 다양한 종류의 데이터 입력 가능.

심벌의 생성:

var sym1 = Symbol();

var sym2 = Symbol();

생성할때마다 새로운 값 생성!

var heart = Symbol( "하트");  :

인수를 전달

Symbol.for( ):

문자열과 연결된 심벌 생성

var sym1 = Symbol.for("club");

심벌과 연결된 문자열 구하기:
Symbol.keyFor( sym1 )
