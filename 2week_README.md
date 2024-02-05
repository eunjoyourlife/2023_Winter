# 포인터
포인터는 변수이다. pointer이라는 말처럼 주소를 가르키는 변수이다. 

예를 들어 int형 변수에 50이란 값이 저장되어 있고 변수의 메모리 시작 주소가 0x0010이라고 하자. 포인터 변수를 하나 선언하여 위의 int형 변수를 저장한다면 50이란 값이 아닌 0x0010이라는 시작 주소를 저장한다.

문법)

타입 변수명 = 데이터;  <- 일반 변수 선언

타입* 변수명 = &일반 변수명;  <- 가리키고자 하는 변수명을 입력

포인터 연산자)

주소 연산자 &는 변수 이름 앞에 사용하여 해당 변수의 메모리 주소 값을 반환한다.

참조 연산자 *는 포인터의 이름이나 주소 앞에 사용하며  해당 주소를 참조하여 주소에 저장되어 있는 값을 반환한다.

# 이중포인터
