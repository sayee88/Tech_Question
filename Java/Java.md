## JAVA 기술 면접질문 정리

<details>
    <summary style="font-size : 16px;"><strong>  Q. Java란 무엇인가요?/특징에 대해 말해보세요.   </strong></summary></br>
   
   자바는 현재 웹 어플리케이션 분야에서 가장 많이 사용되는 언어 중 하나입니다.<br>
   
   특징으로는 
1. 운영체제(OS)에 독립적(이식성이 높음)
2. 객체지향 언어
3. 자동 메모리 관리
4. 멀티 쓰레드 지원
5. 동적 로딩을 지원
6. 네트워크 분산 환경을 지원 등이 있습니다.

</details></br>

<details>
    <summary style="font-size : 16px;"><strong>  Q. 자바의 기본형 데이터 타입에 대해 설명해보세요. / 자바의 참조형 데이터 타입에 대해 설명해보세요.   </strong></summary></br>
   
   논리값(true(참)/false(거짓))을 표현하는 boolean(불리언)형,
단일문자를 표현하는 char(캐릭터)형, 소수점이 없는 정수를 표현하는 byte(바이트), short(숏), int(인트), long(롱), 소 수점이 있는 실수를 표현하는 float(플롯), double(더블) 총 8개의 기본형 데이터 타입이 있습니다. <br>
(32비트 환경에서 char형은 2바이트, byte형은 1바이트, short형은 2바이트, int형은 4바이트, long형은 8바이트, float 은 4바이트, 더블은 8바이트의 크기를 가지고 데이터를 표현한다) <br>
참조형 데이터 타입은 객체의 주소를 저장하고 참조하는 타입으로 클래스(Class), 배열(Array), 열거(enum), 인터페이스(interface)가 있습니다.

</details></br>


<details>
    <summary style="font-size : 16px;"><strong>  Q. JVM의 역할에 대해서 설명하시오.   </strong></summary></br>
   
   JVM은 스택 기반으로 동작하며, Java Byte Code를 OS에 맞게 해석 해주는 역할을 하고 가비지컬렉션을 통해 자동적인 메모리 관리를 해줍니다.

</details></br>


<details>
    <summary style="font-size : 16px;"><strong>  Q. 자바와 자바 스크립트의 차이는?   </strong></summary></br>
   
   둘 모두 자바라는 단어가 들어갈 뿐 직접적인 관련은 없습니다. <br>
자바는 어플리케이션을 개발하기 위한 프로그래밍 언어를 뜻하며 자바스크립트는 정적인 HTML 페이지를 브라우저 상에서 동적으로 보이도록 하는 웹 클라이언트 사이드 언어를 뜻합니다.

</details></br>


<details>
    <summary style="font-size : 16px;"><strong>  Q. 오버라이딩(Overriding)과 오버로딩(Overloading)에 대해 설명해주세요.   </strong></summary></br>
   
   오버라이딩(Overriding)은 상위 클래스에 있는 메소드를 하위 클래스에서 재정의 하는 것을 말하고, <br>
    오버로딩(Overloading)은 매개변수의 개수나 타입을 다르게 하여 같은 이름의 메소드를 여러 개 정의하는 것을 말합니다.

</details></br>


<details>
    <summary style="font-size : 16px;"><strong>  Q. oop란 무엇인가요?   </strong></summary></br>

   일단 객체(Object)란?<br>
   세상에 존재하는 모든 것을 의미, 프로그래밍에서의 객체는 데이터의 분산을 막기 위해 데이터와 기능을 하나로 묶은 그룹을 의미한다.<br><br>
   Object-Oriented Programming의 약자로 객체지향프로그래밍 언어를 뜻하며 <br>
   이러한 객체들을 만들고 이것들을 하나씩 조립, 연결하여 전체 프로그램을 완성하는 기법입니다.
   
   장점 : 유지보수 편리, 재사용성, 생산성 향상, 직관적 코드 분석 가능<br>
   단점 : 설계 단계에 많은 시간 소모, 실행 속도 저하, 코딩 난이도 상승, 지나친 프로그램의 객체화로 실제 세계의 모습을 그대로 반영하지 못함<br>
   특징 : 캡슐화, 상속, 다형성, 추상화<br>
   
</details></br>


<details>
    <summary style="font-size : 16px;"><strong>  Q. 캡슐화를 설명하고 왜 해야하는지 설명하시오.   </strong></summary></br>
   
캡슐화는 객체에 대한 관련 데이터들과 행위를 하나로 묶어 외부에 노출되지 않도록 은닉하는 것을 말합니다. <br>
캡슐화를 하면 객체의 사용자로부터 정보 은폐가 가능하며 객체를 포함한 정보의 손상과 오용을 막을 수 있습니다 . <br>
또한 처리된 결과만 사용하므로 객체의 이식성이 좋습니다.<br>

</details></br>


<details>
    <summary style="font-size : 16px;"><strong>  Q. 다형성이란 무엇이고 동적 바인딩에 대해 설명해 주세요.   </strong></summary></br>
   
   다형성이란 동일한 부모 클래스 타입을 상속받은 후손 클래스 타입들을 부모 타입으로 처리하는 기술을 의미 합니다.<br>
   <strong>(== 다형성이란 하나의 객체에 여러 가지 타입을 대입할 수 있다는 것을 의미합니다.)</strong><br><br>
   
   이 다형성을 지원하기 위해서는 동적 바인딩이 필수적입니다.<br>
   동적 바인딩이란 부모타입으로 참조되는 후손객체의 오버라이딩된 메소드에 적용되며, 컴파일 시에는 부모의 메소드를 정적 바인딩해 두었다가 <br>
   프로그램이 실행될 때 참 조하는 후손의 오버라이딩된 메소드로 연결을 바꾸어 실행하는 것을 말합니다.<br>
   (실행하는 시점에 성격이 결정되는것)<br>

</details></br>



