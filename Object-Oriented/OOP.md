# OOP(Object-Oriented-Programing) 객체지향 프로그래밍

```
 객체들이 서로 유기적으로 동작하는 프로그래밍 이론
 
 객체 지향 프로그래밍은 컴퓨터 프로그램을 명령어의 목록으로 보는 시각에서 벗어나 여러 개의 독립된 단위, 
 즉 "객체"들의 모임으로 파악하고자 하는 것이다. 
 
 각각의 객체는 메시지를 주고받고, 데이터를 처리할 수 있다.
```
<br><br>

## :star:**장점**:star:
1. **코드 재사용 용이** : 상속을 통해 코드의 재사용을 높일 수 있다.


2. **유지보수의 우수성** :  캡슐화를 통해 유지보수가 쉽다.


3. **대형 프로젝트 적합** : 클래스 단위로 모듈화 개발로 업무 분담

<br><br>

## :fearful:**단점**:fearful:
1. **개발속도가 느린 점** : 객체가 처리하려는 것에 대한 정확한 이해가 필요


2. **실행속도가 느린 점** : 객체지향 언어가 대체적으로 실행속도가 느림


3. **코딩 난이도 상승** : 다중 상속과 같은 이유로 복잡도 상승

<br><br>

## **특징**

### 1. :hospital:캡슐화:hospital:
```
데이터와 코드의 형태를 외부로부터 알 수 없게 하고, 
데이터의 구조와 역할, 기능을 하나의 캡슐 형태로 만드는 방법
즉, 낮은 결합도를 유지할 수 있도록 설계하는 것
```

<br>


### 2. :cloud:추상화:cloud:
```
공통의 속성이나 기능을 묶어 이름을 붙이는 것
객체 지향적 관점에서 클래스를 정의하는 것을 바로 추상화라고 정의 내릴 수 있겠다.
```

<br>

### 3. :bow:상속:bow:
```
부모 클래스에 정의된 변수 및 메서드를 자식 클래스에서 상속받아 사용하는 것
```



<br>

### 4. :santa:다형성:santa:
```
프로그램 언어의 다형성은 그 프로그래밍 언어의 자료형 체계의 성질을 나타내는 것으로,
프로그램 언어의 각 요소들(상수, 변수, 식, 오브젝트, 함수, 메소드 등)이
다양한 자료형(type)에 속하는 것이 허가되는 성질을 가리킨다. 
반댓말은 단형성으로, 프로그램 언어의 각 요소가 한가지 형태만 가지는 성질을 가리킨다.
```
**->** 쉽게 말하면 , 다형성이란 하나의 객체에 여러 가지 타입을 대입할 수 있다는 것을 의미합니다

<br>
  
## 다형성을 구별하는 방법
<br>

1. **오버로딩**<br>
메소드 오버로딩은 한 클래스 내에 이미 사용하는 이름의 메소드가 있더라도<br> 특정 규칙을 지킨다면 동일한 이름의 메소드를 정의하도록 허용하는 기술을 말합니다. 특정 규칙은 아래와 같습니다.
```
1. 메소드의 이름이 같아야 한다.

 
2. 매개 변수의 개수 또는 타입이 달라야 한다.

 
3. 매개 변수는 같고, 리턴 타입이 다를 때는 성립하지 않는다.

 
4. 오버로딩된 메소드들은 매개 변수로만 구분될 수 있다.
```
<br>

2. **오버라이딩**<br>
메소드 오버라이딩은 상위 클래스의 메소드를 재정의하는 것을 의미합니다.<br> 주로, 클래스 상속이나 인터페이스 상속을  통해 구현할 수 있습니다

```
조건

1. 오버라이딩이란 메소드의 동작만을 재정의하는 것이므로,
   메소드의 선언부는 기존 메소드와 완전히 같아야 합니다.

    하지만 메소드의 반환 타입은 부모 클래스의 반환 타입으로 
    타입 변환할 수 있는 타입이라면 변경할 수 있습니다.

2. 부모 클래스의 메소드보다 접근 제어자를 더 좁은 범위로 변경할 수 없습니다

3. 부모 클래스의 메소드보다 더 큰 범위의 예외를 선언할 수 없습니다.
```








