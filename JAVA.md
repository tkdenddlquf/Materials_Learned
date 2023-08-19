# 자바 학습
## 언어의 이해
- 컴퓨터와 인간 사이를 연결할 수 있는 매개체이며 컴퓨터에 작업을 시키기 위한 도구
- 기계어인 저급 언어부터 자연어에 가까운 고급 언어까지 다양
- 보통 프로그래밍 언어라고 하면 고급 언어를 의미하는데 C, C++, 자바(Java) 등
- 고급 언어로 작성한 소스 코드는 컴파일러(Compiler)라는 시스템 소프트웨어를 이용해 먼저 기계어로 구성된 실행 코드로 변환

## 역사
- 선마이크로시스템즈(Sun Microsystems)의 제임스 고슬링(James Gosling)이 개발
- 자바의 전신은 1991년 그린 프로젝트(Green Project)로 탄생한 객체 지향 언어인 오크(Oak)
- 1993년 인터넷과 웹이 엄청난 속도로 발전
- 인터넷 환경에 적합하도록 오크를 새롭게 설계한 후 1995년 Java라는 이름으로 발표
- 1996년 자바 1.0을 발표
- 자바 1.2~1.4를 자바 2라고도 하는데, 자바 1.5부터는 1을 빼고 단순하게 자바 5로, 자바 1.6은 자바 6 등으로 지칭

## 특징
- 단순, 견고, 안전, 이식성
- 객체 지향, 함수형 코딩, 독립적 플랫폼, 분산처리 지원, 멀티스레딩 지원

## 활동 분야
- 웹 애플리케이션은 물론 CRM, ERP, SCM 등 기업용 애플리케이션
- 빅데이터, 클라우드, 소셜, 모바일, 사물인터넷 등 혁신 기술에서 커넥티드 카, 스마트폰 및 비디오 게임까지 일상생활과 업무 환경 전반에 밀접하게 연관
- 심지어 전 세계 해양 정보 수집, 인간 두뇌와 근골격계 연구 등에도 다양하게 활용

## 필요성
다른 프로그래밍 언어는 플랫폼 종속되어 있어 프로그램을 실행하려면 운영체제가 제어하는 메모리를 사용해야 하는데, 운영체제마다 메모리를 관리하는 방식이 다르지만, 자바는 자바 가상 머신(JVM)을 사용하기 때문에 플랫폼 독립되어 있다.

## 개발 환경 (이클립스 사용)
- 매우 간단한 자바 프로그램은 메모장에서 .java 파일로 작성한 후 컴파일할 수 있으며, 통합 개발 환경(IDE, Integrated Development Environment)을 이용하면 효율적으로 관리할 수 있다.  
- 대표적인 자바 통합 개발 환경은 이클립스, 넷빈즈(NetBeans), 인텔리J 아이디어(IntelliJ IDEA) 등이 있다.

## 유용한 단축키
- Ctrl + 1 : 코드를 문맥에 맞게 빠르게 교정
- Ctrl + Shift + O : 자동으로 import 문 추가
- Ctrl + Space Bar : 주어진 단어나 문장으로 시작하는 메서드나 변수 표시
- Ctrl + / : 주석 처리, 해체
- Ctrl + Shift + F : 코드의 내용을 보기 좋겍 포맷팅
- Ctrl + F11 : 에디터 뷰에 있는 클래스 실행
- Alt + Shift + R : 선택한 이름을 일괄 변경
- Alt + Shift + Z : 선택한 블록을 try~catch, for, while 문 등으로 자동 완성
- F3 : 메서드, 변수를 선택하고 누으면 해당 메서드가 선언된 곳으로 이동
- 'sysout' + Ctrl + Space Bar : System.out.println() 삽입
- Ctrl + Shift + X / Ctrl + Shift + Y : 소문자를 대문자로, 대문자를 소문자로 치환
- Ctrl + D : 한 행 삭제

## 구조
파일 → 클래스 → 메서드 → 실행문
- 클래스 : 객체 지향 언어에서 프로그램을 개발하는 단위
- 메서드 : 수행할 작업을 나열한 코드의 모임
- 실행문 : 작업을 지시하는 변수 선언, 값 저장, 메서드 호출 등의 코드
- 주석문 : 행 주석(//), 범위 주석(/*   \*/), 문서 주석(/**  */)

## 식별자
- 규칙
  - 문자, 언더바(_), $로 시작해야 한다. 한글도 가능하며, 영문자는 대·소문자를 구분한다.
  - +, - 등 연산자를 포함하면 안 된다.
  - 자바 키워드를 사용하면 안 된다.
  - 길이에 제한이 없다.
- 자바 키워드
  - 데이터 타입 : byte, char, short, int, long, float, double, boolean
  - 접근 지정자 : private, protected, public
  - 제어문 : if, else, for, while, do, break, continue, switch, case
  - 클래스와 객체 : class, interface, enum, extends, implements, new, this, super, instanceof, null
  - 예외 처리 : try, catch, finally, throw, throws
  - 기타 : abstract, assert, const, default, false, final, import, native, package, return, static, strictfp, synchronized, transient, true, void, volatile
- 관례
  - 변수와 메서드는 모두 소문자로 표기. 단, 복합 단어일 때는 두 번째 단어부터 단어의 첫 자만 대문자로 표기
  - 클래스와 인터페이스는 첫 자만 대문자로 표기하고 나머지는 소문자로 표기. 단, 복합 단어일 때는 두 번째 단어부터 단어의 첫 자만 대문자로 표기
  - 상수는 전체를 대문자로 표기. 단, 복합 단어일 때는 단어를 언더바(_)로 연결

## 데이터 타입
- 정수
  |타입|크기|기본값|값의 범위|
  |-|-|-|-|
  |byte|8비트|0|-128 ~ 127|
  |short|16비트|0|-32,768 ~ 32,767|
  |int|32비트|0|-2,147,483,648 ~ 2,147,483,647|
  |long|64비트|0L|-9,223,372,036,854,775,808 ~ 9,223,372,036,854,775,807|
- 문자
  |타입|크기|기본값|값의 범위|
  |-|-|-|-|
  |char|16비트|null|0('\u0000') ~ 65,535('\uFFFF')|
- 실수
  |타입|크기|기본값|값의 범위|
  |-|-|-|-|
  |float|32비트|0.0f|약 -3.4E + 38 ~ 3.4E + 38|
  |double|64비트|0.0d|약 -1.7E + 308 ~ 1.7E + 308|
- 논리
  |타입|크기|기본값|값의 범위|
  |-|-|-|-|
  |boolean|8비트|false|true와 false|

## 변수
- 의미
  - 프로그램은 기억 공간에 데이터를 보관하고, 각 기억 공간을 변수(Variable)로 구분
  - 변수는 데이터를 담는 상자와 같은 것으로 종류가 다양한데, 이를 구분하려고 데이터 타입을 사용
- 리터럴
  - 프로그램 내부에서 값을 정의해 변수를 초기화할 수 있는데, 그 값을 리터럴이라 한다.
- 사용
  - 선언
    ```java
    int weight; // 정수 타입의 weight라는 이름의 변수 선언
    double x, y, z; // 3개의 변수를 ,로 연결해 선언
    ```
  - 초기화
    ```java
    int weight = 50; // int형 weight 변수를 선언 후 50을 대입(선언과 동시에 초기화)
    weight = 30; // weight 변수에 30을 대입(선언 후 초기화)
    ```
- 상수
  - 프로그램 실행 중 변경할 수 없는 데이터를 담는 변수
    > 원주율 값(3.14159)이나 빛의 속도(3×108m/s) 등
  - 상수 이름은 변수와 구분하기 위해 모두 대문자로 표기
  - 반드시 final 키워드로 지정
    ```java
    final double PI = 3.14; // 상수 선언 및 초기화
    ```
- 타입 변환
  - 자동
    ```javas
    double d1 = 5 * 3.14; // 정수 5를 실수 5.0으로 자동 타입 변환
    double d2 = 1; // 정수 1을 실수 1.0으로 자동 타입 변환
    ```
  - 강제
    ```java
    float f = (float)3.14; // double의 3.14를 float로 강제 타입 변환 후 대입
    byte b = (byte)300; // int의 300을 byte로 강제 타입 변환시 데이터 손실 발생
    byte x = (byte)3.14; // double의 3.14를 byte로 강제 타입 변환시 데이터 손실되어 3만 대입
    ```
## 기본 입출력
- 화면에 데이터 출력
  - println() : () 내부의 내용을 출력한 후 행을 바꾼다.
  - print() : () 내부의 내용을 출력만 하고 행은 바꾸지 않는다.
  - printf() : 포맷을 지정해서 출력한다.
    - 정수
      |포맷 명시자|형식|비고|
      |-|-|-|
      |%d|10진수||
      |%o|8진수||
      |%x|16진수||
      |%c|문자||
      |%5d|5자리|빈자리는 공백 처리|
      |%-5d|5자리|빈자리는 공백 처리, 왼쪽 정렬|
      |%05d|5자리|빈자리는 0으로 채운다|
    - 문자열
      |포맷 명시자|형식|비고|
      |-|-|-|
      |%s|문자열||
      |%5s|5자리|빈자리는 공백 처리|
      |%-5s|5자리|빈자리는 공백 처리, 왼쪽 정렬|
    - 실수
      |포맷 명시자|형식|비고|
      |-|-|-|
      |%f|10진수||
      |%e|지수||
      |%4.1f|4자리|소수점 이하 1자리|
      |%-4.1f|4자리|소수점 이하 1자리, 왼쪽 정렬|
      |%04.1f|4자리|소수점 이하 1자리, 빈자리는 0으로 채운다|
    ```java
    // 기본 형식
    // System.out.printf("포맷 명시자", 데이터, 데이터, ...);

    int x = 5;
    double pi = 3.14;

    System.out.printf("x = %d and pi = %f\n", x, pi); // %d와 %f는 포맷 명시자이며, 각각 x와 pi가 대응된다.
    ```
- 키보드로 데이터 입력
  - 프로그램의 첫 행에 다음을 추가해 Scanner 클래스의 경로 이름을 컴파일러에 알린다.
    ```java
    import java.util.Scanner;
    ```
  - 키보드로 데이터를 입력받으려고 System.in 객체와 연결된 Scanner 객체를 생성한다.
    ```java
    Scanner in = new Scanner(System.in);
    ```
  - Scanner 클래스가 제공하는 다양한 메서드를 이용해 키보드로 데이터를 입력받는다.
    ```java
    int x = in.nextInt(); // 정수를 읽어 변수 x에 대입한다.
    ```
  - Scanner 클래스가 제공하는 데이터 입력 메서드
    - next() : String 타입
    - nextByte() :  byte타입
    - nextShort() :  short타입
    - nextInt() :  int타입
    - nextLong() :  long타입
    - nextFloat() :  float타입
    - nextDouble() :  double타입
    - nextLine() : String 타입

## 연산자
- x + y 에서 x, y는 피연산자 +는 연산자를 의미
- 자바 가상 머신은 기본적으로 32비트 단위로 계산
  ```java
  byte b1 = 1;
  byte b2 = 2;
  byte b3 = b1 + b2; // 오류 발생
  ```
- 종류
  |연산자 종류|연산자|기능 설명|피연산자 수|
  |-|-|-|-|
  |증감|++, --|1만큼 증가 또는 감소|단항|
  |산술|+, -, *, /, %|사칙 연산과 모듈로 연산|이항|
  |시프트|>>, <<, >>>|비트를 좌우로 이동|이항|
  |부호|+, -|부호를 변환|단항|
  |비교|>, <, >=, <=, ==, !=, instanceof|데이터 값을 비교하거나 데이터 타입을 비교|이항|
  |비트|&, \|, ~, ^|비트 단위의 AND, OR, NOT, XOR)|단항, 이항|
  |논리|&&, \|\|, !, ^|논리적 AND, OR, NOT, XOR)|단항, 이항|
  |조건|(expr) ? x : y|expr에 따라 x또는 y로 값을 결정|삼항|
  |대입|=, +=, -=, *=, /=, &=, \|=, ^=, >>=, <<=, >>>=|오른쪽 값을 연산해 왼쪽에 대입|이항|
- 산술 연산자
  - 연산할 두 피연산자의 데이터 타입이 다르면 큰 범위의 타입으로 일치시킨 후 연산 수행
  - 논리 타입을 제외한 기초 타입을 피연산자로 사용. 단, % 연산자는 정수 타입만 사용
  - 덧셈 연산자는 문자열을 연결하는 데도 사용. 문자열과 덧셈을 하는 데이터는 먼저 문자열로 변환한 후 서로 연결
- 비교 연산자
  - 비교 연산자는 논리 타입을 제외한 기초 타입에만 사용할 수 있지만 ==와 !=는 모든 기초 타입에 사용
    |연산식|설명|
    |-|-|
    |x == y|x와 y는 같은가?|
    |x != y|x와 y가 다른가?|
    |x > y|x는 y보다 큰가?|
    |x >= y|x는 y보다 크거나 같은가?|
    |x < y|x는 y보다 작은가?|
    |x <= y|x는 y보다 작거나 같은가?|
- 논리 연산자
  - 논리 연산자는 피연산자의 조건을 결합해서 true와 false를 조사하며, 논리 타입에만 사용
    |a|b|!a|a && b|a \|\| b|a ^ b|
    |-|-|-|-|-|-|
    |false|false|true|false|false|false|
    |false|true|true|false|true|true|
    |true|false|false|false|true|true|
    |true|true|false|true|true|false|
  - &&, ||는 연산자의 앞 조건식의 결과에 따라 뒤 조건식의 실행 여부를 결정하며, 이를 쇼트서킷이라 한다.
- 비트, 시프트 연산자
  - 비트 연산자와 시프트 연산자는 정수 타입에만 사용
  - 종류
    - & : 두 비트가 모두 1일 때만 1이며, 나머지는 모두 0이다.
    - | : 두 비트가 모두 0일 때만 0이며, 나머지는 모두 1이다.
    - ^ : 두 비트가 서로 다를 때는 1, 동일할 때는 0이다.
    - ~ : 1을 0으로, 0을 1로 바꾼다.
    ```java
    System.out.printf("%x\n", 0b0101 & 0b0011); // 1
    System.out.printf("%x\n", 0b0101 | 0b0011); // 7
    System.out.printf("%x\n", 0b0101 ^ 0b0011); // 6
    System.out.printf("%x\n", (byte) ~0b00000001); // fe
    System.out.printf("%x\n", 0b0110 >> 2); // 1
    System.out.printf("%x\n", 0b0110 << 2); // 18

    int i1 = -10;
    int i2 = i1 >> 1;
    int i3 = i1 >>> 1;
    System.out.printf("%x -> %d\n", i1, i1); // ffffff6 -> -10
    System.out.printf("%x -> %d\n", i2, i2); // ffffffb -> -5
    System.out.printf("%x -> %d\n", i3, i3); // ffffffb -> 2147483643
    ```
- 대입 연산자
  - 오른쪽에 있는 연산식의 결과 값을 왼쪽에 있는 변수에 대입
    ```java
    int weight = 50;
    weight = weight + 10;
    ```
  - 복합 대입 연산자의 종류
    |연산식|설명|
    |-|-|
    |a += b|a = a + b와 동일|
    |a -= b|a = a - b와 동일|
    |a *= b|a = a * b와 동일|
    |a /= b|a = a / b와 동일|
    |a %= b|a = a % b와 동일|
    |a &= b|a = a & b와 동일|
    |a \|= b|a = a | b와 동일|
    |a ^= b|a = a ^ b와 동일|
    |a >>= b|a = a >> b와 동일|
    |a <<= b|a = a << b와 동일|
  - 부호, 증감 연산자
    - 숫자를 나타내는 기초 타입에 사용하며 피연산자의 부호를 그대로 유지하거나 반전
    - 증감 연산자는 변수의 위치에 따라 의미가 다르다.
    - 종류
      |종류|설명|비고|
      |-|-|-|
      |+|부호 유지||
      |-|부호 반전||
      |++x|연산 전 x 값 중가|전위 증가|
      |x++|연산 후 x 값 중가|후위 증가|
      |--x|연산 전 x 값 감소|전위 감소|
      |x--|연산 후 x 값 감소|후위 감소|
  - 조건 연산자
    - 조건 연산자(?:)는 조건식이 true이면 결과 값은 앞 연산식의 값이 되고 false이면 결과 값은 뒤 연산식의 값이 된다.
    - 조건 연산자도 쇼트서킷 로직을 이용하기 때문에 조건식에 따라 앞 연산식과 뒤 연산식 중 하나만 실행
  - 우선 순위
    |종류|설명|
    |-|-|
    |[], ., (), ++, --|배열 접근, 객체 접근, 메서드 호출, 후위 증가, 후위 감소|
    |+x, -x, ++x, --x, ~(비트), !(논리)|부호 +/-, 선위 증가, 선위 감소, 비트 부정, 논리 부정|
    |(), new|타입 변환, 객체 생성|
    |*, /, %|곱셈, 나눗셈, 모듈로|
    |+, -|덧셈, 뺄셈|
    |>>, <<, <<<|시프트|
    |>, <, >=, <=, instanceof|비교|
    |==, !=|동등 여부|
    |&|비트 AND|
    |^|비트 XOR|
    |\||비트 OR|
    |&&|조건 AND|
    |\|\||조건 OR|
    |?:|조건 연산|
    |=, +=, -=, *=, /=, &=, \|=, ^=, >>=, <<=, >>>=|대입|
  - 결합 규칙
    ```java
    x = y = z = 3; // 3을 z, y, x 순으로 대입
    z = x * y / z % 2; // 연산자의 우선순위가 모두 같으므로 순서대로 연산
    z = x++ + --y * x // y에 1을 더한 후 x를 곱한 뒤 x를 더한 값을 대입해 준 뒤 x에 1을 더한다
    ```
    
## 제어문
제어문은 실행문의 수행 순서를 변경
- 종류  
  - 조건문 : 조건에 따라 실행문을 선택을 할 때 사용
    - 단순 if 문
      ```
      if(조건식)
      {
       실행문들;
      }
      ```
    - if~else 문
      ```
      if(조건식)
      {
       실행문들;
      }
      else
      {
       실행문들;
      }
      ```
    - 다중 if 문
      ```
      if(조건식)
      {
       실행문들;
      }
      else if(조건식)
      {
       실행문들;
      }
      else if(조건식)
      {
       ...
      }
      else
      {
       실행문들;
      }
      ```
    - 중첩 if 문
      ```
      // if 문에 다른 if 문이 포함되는 것을 중첩 if 문이라고 한다
      // else 문을 사용할때 주의 필요
      if(조건식)
      {
       if(조건식)
       {
        실행문들;
       }
      }
      ```
    - switch 문
      ```
      // 0개 이상의 case 절과 0이나 1개의 default 절로 구성
      switch(연산식)
      {
       case 값:
        실행문들;
       case 값:
        실행문들;
       ...
       default:
        실행문들;
      }
      ```
  - 반복문 : 조건에 따라 같은 처리를 반복
    - 반복할 조건을 아는 경우 while 문, do~while 문 사용
      - while 문
        ```
        // 조건문이 거짓인 경우에는 작동하지 않는다
        while(조건식)
        {
         반복 실행문들;
        }
        // 조건문이 항상 참인 경우 반복문을 탈출할 실행문 필요
        // 조건문이 항상 거짓인 경우 도달하지 않는 코드라는 오류 발생
        ```
      - do~while 문
        ```
        // 조건문이 거짓인 경우에도 한번은 작동한다
        do
        {
         반복 실행문들;
        } while(조건식);
        ```
    - 반복할 횟수를 아는 경우 for 문 사용
      - for문
        ```
        // 조건문이 거짓인 경우 실행문과 증감식이 작동하지 않는다
        // 초기식, 조건식, 증감식에 아무것도 넣지 않은 경우 무한반복
        for(초기식; 조건식; 증감식)
        {
         반복 실행문들;
        }
        ```
        ```java
        for(int i = 0; i < 2; i ++)
        {
         System.out.println(i); // 0, 1을 출력한다
        }
        ```
  - 분기문
    - break 문
      ```
      while(조건식)
      {
       while(조건식)
       {
        break; // 가장 안쪽의 while 문 만 탈출한다
       }
      }
      
      out : while(조건식)
      {
       while(조건식)
       {
        break out; // out 레이블의 while 문을 탈출한다
       }
      }
      ```
    - continue 문
      ```
      while(조건식)
      {
       continue; // continue 다음의 실행문들을 건너뛴다
      }
      ```
  - 메서드
    - 필요성
      - 중복 코드를 줄이고 코드를 재사용할 수 있다
      - 코드를 모듈화해 가독성을 높이므로 프로그램의 품질을 향상시킨다
    - 구조
      ```java
      // public : 접근 지정자
      // static : 객체를 생성하지 않고 실행할 수 있다
      // int : 반환 타입
      // sum : 메서드 이름
      // int i1, int i2 : 매개변수 목록
      public static int sum(int i1, int i2)
      {
       return i1 + i2; // i1 + i2의 타입과 반환 타입이 일치해야 한다.
      }
      ```
    - 메서드의 호출과 반환
      - 메서드를 호출하면 제어가 호출된 메서드(callee)로 넘어갔다가 실행을 마친 후 호출한 메서드(caller)로 다시 돌아온다.
      - return 문을 사용하면 메서드의 실행 도중에도 호출한 메서드로 제어를 넘길 수 있다.
    - 값 전달
      ```java
      int x = 0;
      increment(x);

      public static void increment(int n)
      {
       n++;
      }
      // increment() 메서드 호출 전 x는 0
      // increment() 메서드 시작할 때 n은 0
      // increment() 메서드 끝날 때 n은 1
      // increment() 메서드 호출 후 x는 0
      ```
    - 메서드 오버로딩
      - 메서드 시그너처(Method Signature) : 메서드 이름과 매개변수의 개수, 데이터 타입, 순서를 의미
      - 메서드 이름은 같지만 메서드 시그니처가 다른 메서드를 정의하는 것을 메서드 오버로딩(Method Overloading)이라고 한다.

## 객체 지향
- 객체의 개념
  - 소프트웨어 객체는 현실 세계의 객체를 필드와 메서드로 모델링한 것
  - 소프트웨어 객체는 상태를 필드(Field)로 정의하고, 동작을 메서드(Method)로 정의.
  - 필드는 객체 내부에 선언된 변수를 의미하고, 메서드는 객체 내부에 정의된 동작
- 절차 지향 프로그래밍
  - 일련의 동작을 순서에 맞추어 단계적으로 실행하도록 명령어를 나열
  - 데이터를 정의하는 방법보다는 명령어의 순서와 흐름에 중점
  - 수행할 작업을 예상할 수 있어 직관적인데, 규모가 작을 때는 프로그래밍과 이해하기가 용이
  - 소프트웨어는 계산 위주이므로 절차 지향 프로그래밍이 적합
- 객체 지향 프로그래밍
  - 프로그램 구현에 필요한 객체를 파악하고 각각의 객체들의 역할이 무엇인지를 정의하여 객체들 간의 상호작용을 통해 프로그램을 만드는 것
  - 현실 세계를 객체 단위로 프로그래밍하며, 객체는 필드(데이터)와 메서드(코드)를 하나로 묶어 표현
- 특징
  - 캡슐화(정보 은닉) : 관련된 필드와 메서드를 하나의 캡슐처럼 포장해 세부 내용을 외부에서 알 수 없도록 감추는 것
  - 상속 : 자녀가 부모 재산을 상속받아 사용하듯이 상위 객체를 상속받은 하위 객체가 상위 객체의 메서드와 필드를 사용하는 것
  - 다형성 : 대입되는 객체에 따라서 메서드를 다르게 동작하도록 구현, 실행 도중 동일한 이름의 다양한 구현체 중에서 메서드를 선택 가능

## 클래스 선언과 객체 생성
- 추상화
  - 현실 세계의 객체는 수많은 상태가 있고 다양한 동작을 하지만, 클래스에 모두 포함하기는 어렵기에 추상화(Abstraction)하는 과정이 필요
  - 추상화는 현실 세계의 객체에서 불필요한 속성을 제거하고 중요한 정보만 클래스로 표현하는 일종의 모델링 기법
  - 사람마다 추상화하는 기법이 같지 않으므로 각 개발자는 클래스를 다르게 정의 가능
- 클래스 선언
  ```java
  // class : 클래스 키워드
  // ReturnN : 클래스 이름으로 소스 파일 이름과 동일해야 한다
  // 필드 : 객체의 속성을 나타낸다
  // 메서드 : 객체의 동작을 나타낸다
  public class ReturnN
  {
    int n = 0; // 필드
  
    int getN() // 메서드
    {
      return n;
    }
  }
  ```
  - 보통 소스 파일마다 하나의 클래스를 선언하지만, 2개 이상의 클래스를 하나의 파일로 선언 가능
  - 하나의 파일에 클래스가 둘 이상 있다면 하나만 public으로 선언할 수 있고, 해당 클래스 이름은 소스 파일 이름과 동일해야 함
- 객체 생성과 참조 변수
  ```
  클래스이름 변수; // 클래스는 참조 타입이므로 참조 변수 또는 참조 타입 변수라고 한다
  변수 = new 클래스이름(); // 클래스이름()을 생성자라고 한다
  // 변수를 생략하거나 한 문장으로 변수 선언과 객체 생성 또한 가능하다
  ```

## 클래스의 구성 요소와 멤버 접근
- 클래스의 구성 요소
  - 멤버(필드, 메서드)
  - 생성자
  > 지역 변수는 메서드 내부에 선언된 변수. 매개 변수도 일종의 지역 변수이다
- 필드와 지역 변수의 차이
  - 필드는 기본 값이 있지만, 지역 변수는 기본 값이 없어 반드시 초기화
  - 필드는 클래스 전체에서 사용할 수 있지만, 지역 변수는 선언된 블록 내부의 선언된 후에서만 사용 가능
  - 필드와 달리 지역 변수는 final로만 지정 가능
- 클래스 내부에서 멤버 접근
  ```
  this.필드 // 또는 필드로 사용
  this.메서드 // 또는 메서드로 사용
  ```
- 클래스 외부에서 멤버 접근
  ```java
  // myCircle : 사용하려는 외부 객체 이름
  // . : 객체와 객체 멤버를 연결하는 연산자
  // radius : 필드 이름
  // findArea : 메서드 이름
  myCircle.radius; // 인스턴스 변수
  myCircle.findArea(); // 인스턴스 메서드
  ```

## 접근자와 설정자
- 필요성
  클래스 내부에 캡슐화된 멤버를 외부에서 사용하기 위해
- 접근자와 설정자
  - private으로 지정된 필드에 값을 반환하는 접근자와 값을 변경하는 설정자는 공개된 메서드
  - 일반적으로 접근자는 get, 설정자는 set으로 시작하는 이름을 사용
  - 필드 이름을 외부와 차단해서 독립시키기 때문에 필드 이름 변경이나 데이터 검증도 가능

## 생성자
- 생성자의 의미와 선언
  - 생성자의 역할 : 객체를 생성하는 시점에서 필드를 다양하게 초기화
  - 생성자의 선언 방식
    ```
    클래스이름(...) {...} // 일반적으로 public으로 선언하지만 아닐 수도 있다
    ```
    - 생성자 이름은 클래스 이름과 같다.
    - 생성자의 반환 타입은 없다.
    - 생성자는 new 연산자와 함께 사용하며, 객체를 생성할 때 호출한다.
    - 생성자도 오버로딩할 수 있다
  - 생성자 사용
    ```
    클래스이름 변수 = new 클래스이름(); // 클래스이름()을 생성자라고 한다
    ```
- 기본 생성자
  - 모든 클래스는 최소한 하나의 생성자가 있음
  - 만약 생성자를 선언하지 않으면 컴파일러가 자동으로 기본 생성자(Default Constructor)를 추가
  - 기본 생성자는 매개변수도 없고 본체에서 실행할 내용도 없는 생성자
- 생성자 오버로딩
  생성자도 메서드처럼 오버로딩(Overloading) 가능
- this와 this()
  ```java
  // this
  class Square
  {
    private double side; // 멤버 필드

    public void setRadius(double side)
    {
      this.side = side; // 매개변수 = 멤버 필드의 형식이다
    }
  }
  
  // this()
  class Circle
  {
    private double radius; // 멤버 필드

    public Circle(double radius)
    {
      this.radius = radius; // 매개변수 = 멤버 필드의 형식이다
    }

    public Circle()
    {
      this(2.0); // 같은 클래스의 다른 Circle() 생성자를 호출해 매개변수로 2.0을 넣는다
    }
  }
  ```
- 연속 호출
  반환 타입이 void인 setName(String name), setAge(), sayHello()라는 메서드를 가진 Person 클래스가 있다고 가정
    ```java
    Person person = new Person();
    person.setName("민국");
    person.setAge(21);
    person.sayHello();
    // 메서드를 호출할 때마다 새로운 실행문을 사용해야 하므로 번거롭고 가독성도 떨어진다
    ```
  setName()과 setAge()의 반환 타입이 this라면
    ```java
    Person person = new Person();
    person.setName("민국").setAge(21).sayHello(); // 한번에 호출이 가능하다
    ```

## 정적 멤버
- 인스턴스 멤버와 정적 멤버
  - 자바는 static 키워드로 클래스의 필드를 공유할 수 있도록 지원
  - 인스턴스 변수 : static 키워드로 지정되지 않아 공유되지 않은 필드로 인스턴스마다 자신의 필드를 생성
  - 정적 변수 혹은 클래스 변수 : static 키워드로 지정하여 모든 인스턴스가 공유하는 필드
  - 인스턴스 변수는 객체별로 관리. 객체를 생성할 때 인스턴스 변수도 객체가 소멸될 때는 자동으로 소멸
  - 정적 변수는 클래스 로더가 클래스를 메서드 영역에 적재할 때 생성
  - 정적 메서드의 유의 사항
    - 객체와 관련된 인스턴스 변수를 사용할 수 없다.
    - 객체와 관련된 인스턴스 메서드를 호출할 수 없다.
    - 객체 자신을 가리키는 this 키워드를 사용할 수 없다.
- 정적 멤버의 활용
  ```
  // 정적 멤버는 일반적으로 클래스 이름과 연결해서 사용한다
  클래스이름.정적변수이름;
  클래스이름.정적메서드이름();
  ```
  - 상수는 변경되지 않는 변수이기 때문에 final 키워드로 지정하지만 final로만 지정하면 객체마다 자신의 기억 공간을 차지
  - 상수는 값이 변경되지 않으므로 객체마다 따로 기억 공간을 할당할 필요가 없다. 따라서 static final로 지정해서 선언
  ```
  // static : 모든 객체가 공유한다
  // final : 초깃값이 대입되면 더 이상 수정할 수 없다
  static final 데이터형 상수 = 초깃값;
  ```
- 정적 블록
  정적 변수의 초기화 과정이 for 문이나 오류 처리처럼 복잡하다면 과정이 간단하지 않다. 대신에 정적 변수의 초기화가 복잡할 때는 다음과 같이 정적 블록을 사용할 수 있다.
  ```
  static String name = "민국";
  static
  {
    name = "만국";
  }
  // name을 호출할 경우 "만국"이 호출된다
  ```

## 문자열
- 문자열의 선언과 생성
  - 문자열 리터럴은 내부적으로 new String()을 호출해 생성한 객체
    ```
    String 변수; // String 타입의 변수 선언
    변수 = "문자열";
    // String 변수 = new String("문자열");과 같다
    ```
  - 내용이 같은 문자열 리터럴이라면 더 이상 새로운 String 객체를 생성하지 않은 채 기존 리터털을 공유
    ```java
    String s1 = "hello";
    String s2 = "hello";
    // s1과 s2는 동일한 String 객체를 가리킨다
    ```
- 문자열의 비교
  - ==와 != 연산자는 두 문자열의 내용을 비교하는 것이 아니라 동일한 객체인지 검사
  - String 클래스에서 제공하는 문자열 비교 메서드
    |메서드|설명|
    |-|-|
    |int compareTo(String s)|문자열을 사전 순으로 비교해 정수 값을 반환|
    |int compareToIgnoreCase(String s)|대소문자를 무시하고, 문자열을 사전 순으로 비교|
    |boolean equals(String s)|주어진 문자열 s와 현재 문자열을 비교한 후 true/false를 반환|
    |boolean equalsIgnoreCase(String s)|주어진 문자열 s와 현재 문자열을 대소문자 구분 없이 비교한 후 true/false를 반환|
    |char charAt(int index)|index가 지정한 문자를 반환|
    |String concat(String s)|주어진 문자열 s를 현재 문자열 뒤에 붙인다|
    |boolean contains(String s)|문자열 s를 포함하는지 조사|
    |boolean endsWith(String s)|끝나는 문자열이 s인지 조사|
    |boolean isEmpty()|문자열의 길이가 0이면 true를 반환|
    |int length()|문자열의 길이를 반환|
    |boolean startsWith(String s)|시작하는 문자열이 s인지 조사|
    |String substring(int index)|index부터 시작하는 문자열의 일부를 반환|
    |String toLowerCase()|문자열을 모두 소문자로 변환|
    |String toUpperCase()|문자열을 모두 대문자로 변환|
    |String trim()|문자열 앞뒤에 있는 공백을 제거한 후 반환|

## 배열 기초
- 배열
  - 변수들을 연속된 집합체로 모아 놓은 것으로 동일한 이름을 사용하여 인덱스로 각 항목을 구분
  - 연속된 메모리 공간에 존재하기 때문에 관리하기 편리
- 배열의 선언과 생성
  - 배열의 선언 : 실제는 배열 변수의 선언
    ```java
    int[] scores; // 혹은 int scores[];로 선언
    // int scores[5];와 같은 선언은 불가
    ```
  - 배열의 선언과 생성 : 실제는 배열 변수의 선언과 초기화
    ```java
    int[] scores1 = new int[5]; // 5는 배열의 크기
    int[] scores2 = new int[] { 100, 90, 50, 95, 85 }; // 이처럼 선언 가능
    ```
    잘못된 방식
    ```java
    int[] scores;
    scores = { 100, 90, 50, 95, 85 };
    ```
- 배열 원소의 접근
  ```
  배열이름[인덱스];
  ```
- 배열의 크기
  - 배열이 생성될 때 배열의 크기가 결정
  - 배열의 length 필드가 배열의 크기를 나타낸다
- 다차원 배열
  - 배열의 배열
    ```java
    int[][] scores = new int[3][5]; // 2개의 대괄호는 2차원 배열을 표시
    // 3은 행의 개수, 5는 열의 개수
    ```
  - 선언과 초기화
    ```java
    int[][] scores = {{ 100, 90, 50, 95, 85 }, { 70, 60, 80, 75, 40 }, { 60, 30, 10, 80, 90 }};
    ```
- 동적 배열
  - 처리할 데이터의 개수가 고정된 경우가 아니라면 정적 배열은 자원을 낭비하거나 프로그램을 다시 컴파일
  - 자바는 크기가 유동적인 배열을 지원하기 위하여 ArrayList 클래스를 제공
  - ArrayList 객체 생성
    ```
    // 참조타입이 기초 타입이라면 integer, Long, Short, Float, Double 등을 사용
    ArrayList<참조타입> 참조변수 = new ArrayList<>();
    ```
  - ArrayList 원소 접근
    ```
    참조변수.add(데이터);
    참조변수.remove(인덱스번호);
    참조변수.get(인덱스번호);
    참조변수.size();
    ```
    
## 배열 응용
- 배열을 위한 반복문
  - for~each 반복문 : JDK 5부터 도입된 것으로 for 문을 개선한 방식. 특정 원소를 나타내기 위한 인덱스를 사용하지 않음
    ```
    // 배열_혹은_컬렉션에서 가져올 항목이 있다면 변수에 대입
    // 배열_혹은_컬렉션에서 가져올 항목이 없다면 for 문 탈출
    for (데이터타입 변수 : 배열_혹은_컬렉션)
    {
      실행문;
    }
    ```
- 배열 전달
  ```java
  int[] x = new int[] { 0, 1, 2, 3, 4 };

  public increment(int[] n)
  {
    n[0] = 1;
  }

  increment(x); // x[0]의 값이 1로 변경
  ```
- 가변 개수 인수
  - JDK 5부터는 메서드에도 데이터 타입이 같은 가변 개수(variable length)의 인수를 전달 가능
  - 한 개의 가변 개수 매개변수만 사용 가능하며 가변 개수 매개변수는 마지막에 위치
  - 가변 개수 인수를 가진 메서드를 호출하면 내부적으로 배열을 생성하여 처리
  ```java
  int[] x = new int[] { 0, 1, 2, 3, 4 };
  
  void printN(int... n)
  {
    for(int a : n) System.out.println(a);
  }

  printN(x); // x값을 순서대로 출력
  ```
- 객체의 배열
  - 객체 배열은 객체를 참조하는 주소를 원소로 구성
    ```java
    Ball[] balls = new Ball[5]; // 5개의 Ball 객체를 생성하는 것이 아닌 참조할 변수를 준비
    ```
  - 생성자를 호출하여 Ball 객체를 생성해야 함
    ```java
    Ball[] balls = new Ball[5];

    for (int i = 0; i < 3; i++) balls[i] = new Ball();
    ```
- 매개변수로 객체 전달
  메서드의 인자로 객체를 받는 경우에도 전달 가능

## 디버깅
- 오류의 종류
  - 문법 오류
    > 실행문을 세미콜론으로 마쳐야 한다
  - 내용 오류
    > n의 2배를 구하려 할때 n * n을 진행한 경우
  - 연산이 불가능한 경우
    > n / 0의 경우 n을 0으로 나눌수 없다
- 이클립스를 이용한 디버깅 과정
  - 이클립스는 에디터 뷰에 문법 오류는 알려주지만 논리 오류는 알려주지 않는다.
  - 논리 오류는 프로그램 실행 도중에 변수 상태를 추적하는 것이 가장 기본적인 오류 점검 방식
- 디버깅 명령어와 이클립스 단축키
  |명령어|단축키|설명|
  |-|-|-|
  |Step Into|F5|한 행씩 실행하며, 메서드를 만나면 내부로 진입|
  |Step Over|F6|한 행씩 실행하며, 메서드를 만나도 내부로 진입하지 않음|
  |Run to Line|Ctrl + R|다음 중단점까지 프로그램을 실행|
  |Resume|F8|중단된 프로그램을 다시 실행|
  |Terminate|Ctrl + F2|프로그램 종료|

## 상속
- 필요성
  공통적인 성분을 부모 클래스에서 한번만 정의하기 때문에 코드가 간결하고 편리
- 상속과 클래스 멤버
  - 자식 클래스는 부모 클래스에서 물려받은 멤버를 그대로 사용하거나 변경할 수 있고, 새로운 멤버 추가 가능
  - 자식 클래스는 대체로 부모 클래스보다 속성이나 동작이 더 많음

## 클래스 상속
- 부모· 자식 클래스의 관계
  - is-a (상속 관계)
    > a는 b이다
  - has-a (소유 관계)
    > a는 b가 있다
- 상속의 선언
  extends 키워드 사용하며, 다중 상속 불가
  ```java
  // 부모 클래스
  class SuperClass
  {
    // 필드
    // 메서드
  }
  
   // 자식 클래스
  class SubClass extends SuperClass // extends SuperClass, SuperClass2와 같이 다중 상속 불가
  {
    // 필드
    // 메서드
  }
  ```
  
## 메서드 오버라이딩
- 의미
  메서드 오버라이딩(Method Overriding)은 물려받은 메서드를 자식 클래스에게 맞도록 수정하는 것
- 규칙
  - 부모 클래스의 메서드와 동일한 시그너처를 사용, 반환 타입까지 동일해야 한다
  - 부모 클래스의 메서드보다 접근 범위를 더 좁게 수정할 수 없다
  - 추가적인 예외(Exception)가 발생할 수 있음을 나타낼 수 없다
- 오버라이딩 불가
  - private 메서드 : 부모 클래스 전용이므로 자식 클래스에 상속되지 않는다
  - 정적 메서드 : 클래스 소속이므로 자식 클래스에 상속되지 않는다
  - final 메서드 : final 메서드는 더 이상 수정할 수 없으므로 자식 클래스가 오버라이딩할 수 없다
- 부모 클래스의 멤버 접근
  - 자식 클래스가 메서드를 오버라이딩하면 자식 객체는 부모 클래스의 오버라이딩된 메서드를 숨김
  - 숨겨진 메서드를 호출하려면 super 키워드를 사용한다.
  - super는 현재 객체에서 부모 클래스의 참조를 의미
- 메서드 오버라이딩과 메서드 오버로딩
  |비교 요소|메서드 오버라이딩|메서드 오버로딩|
  |-|-|-|
  |메서드 이름|동일|동일|
  |매개변수|동일|다름|
  |반환 타입|동일|무관|
  |상속 관계|필요|필요 없음|
  |예외와 접근 범위|제약|제약 없음|
  |바인딩|호출할 메서드를 실행 중 결정하는 동적 바인딩|호출할 메서드를 컴파일할 때 결정하는 정적 바인딩|

## 패키지
- 의미
  파일 시스템의 폴더를 이용하며 클래스 파일을 묶어서 관리하기 위한 수단
- 장점
  - 패키지마다 별도의 이름 공간(Namespace)이 생기기 때문에 클래스 이름의 유일성을 보장
  - 클래스를 패키지 단위로도 제어할 수 있기 때문에 좀 더 세밀하게 접근 제어
- 대표적인 패키지
  - java.lang 패키지는 import 문을 선언하지 않아도 자동으로 임포트되는 자바의 기본 클래스를 모아 둔 것
  - java.awt 패키지는 그래픽 프로그래밍에 관련된 클래스를 모아 둔 것
  - java.io 패키지는 입출력과 관련된 클래스를 모아 둔 것
- 패키지의 선언
  - 주석문을 제외하고 반드시 첫 라인에 위치
  - 패키지 이름은 모두 소문자로 명명하는 것이 관례
  - 일반적으로 패키지 이름이 중복되지 않도록 회사의 도메인 이름을 역순으로 사용
    > package com.hankuk.people;의 형식으로 선언 및 명명
- 패키지의 사용
  다른 패키지에 있는 공개된 클래스를 사용하려면 패키지 경로를 컴파일러에게 알려줘야 한다
  > 패키지이름.클래스의 형태로 사용
- import 문
  - 패키지의 경로를 미리 컴파일러에게 알려주는 문장
    > import 패키지이름.클래스와 같이 사용
  - import 문은 소스 파일에서 package 문과 첫 번째 클래스 선언부 사이에 위치
    > import 패키지이름.*을 사용한 경우 패키지이름에 포함된 모든 클래스를 뜻한다
- 정적 import 문
  - 패지키 단위로 임포트하지 않고 패키지 경로와 정적 메서드를 함께 임포트
  - import static 을 사용하여 클래스명 없이 바로 사용, 클래스 내에 동일한 이름의 메소드가 있으면 클래스의 메소드가 우선

## 자식 클래스와 부모 생성자
- 자식 생성자를 호출하면 부모 생성자도 자동으로 호출
  > 부모 생성자가 없는 경우 에러 발생
- 자식 생성자는 첫 행에 부모 생성자 호출 코드가 있음
  > 없다면 컴파일러가 super(); 코드를 추가
- 자식 생성자의 첫 행에 인위적 부모 생성자 호출
  > 반드시 첫행에 나타나야 한다

## 상속과 접근 제어
- 접근 지정자의 접근 범위
  |접근 지정자|동일 클래스|다른 패키지|자식 클래스|전체|
  |-|-|-|-|-|
  |public|접근 가능|접근 가능|접근 가능|접근 가능|
  |protected|접근 가능|접근 가능|접근 가능|접근 불가|
  |default|접근 가능|접근 가능|접근 불가|접근 불가|
  |private|접근 가능|접근 불가|접근 불가|접근 불가|
- 접근 지정자 사용 시 주의 사항
  - private 멤버는 자식 클래스에 상속되지 않는다
  - 클래스 멤버는 어떤 접근 지정자로도 지정할 수 있지만, 클래스는 protected와 private로 지정할 수 없다
  - 메서드를 오버라이딩할 때 부모 클래스의 메서드보다 가시성을 더 좁게 할 수는 없다

## final 클래스와 메서드
- final 클래스
  - 더 이상 상속될 수 없는 클래스
  - 대표적인 final 클래스로는 String 클래스
- final 메서드
  final 클래스는 내부의 모든 메서드를 오버라이딩할 수 없으므로, 특정 메서드만 오버라이딩하지 않도록 하려면 final 메서드로 선언

## 타입 변환과 다형성
- 객체의 타입 변환
  - 참조 타입인 객체도 기초 타입 데이터처럼 타입 변환 가능
  - 상속 관계일 경우만 타입 변환 가능
  - 객체 타입 변환도 자동 타입 변환과 강제 타입 변환이 있다
- 타입 변환
  ```java
  public class Person
  {
    String name = "사람";

    void whoami()
    {
      System.out.println("나는 사람이다");
    }
  }
  ```
  ```java
  public class Student extends Person
  {
    int number = 7;

    void work()
    {
      System.out.println("나는 공부한다");
    }
  }
  ```
  - 자동 타입 변환
    ```java
    Student s = new Student();
    Person p = s; // 자동으로 타입 변환 p = (Person)s와 동일
    // p.number = 1;
    // p.work();
    // number와 work()는 부모 타입에 없는 멤버이므로 부모 타입 변수에서 볼 수 없다
    p.whoami(); // Person 타입 멤버이므로 호출 가능
    ```
  - 강제 타입 변환
    ```java
    // 오류 발생
    Person p = new Person();
    Student s = (Student)p;
    
    // 강제 타입 변환 가능
    Student s1 = new Student();
    Person p1 = s1;
    Student s2 = (Student)p1; // 부모 타입 변수지만 자식 객체를 가리킨다
    ```
- 타입 변환된 객체의 구별
  ```
  // 변수 : 객체를 참조하는 변수
  // instanceof : boolean 값을 반환
  // 타입 : 클래스 이름 혹은 인터페이스 이름
  변수 instanceof 타입
  ```
- 타입 변환을 이용한 다형성
  ```java
  static void downcast1(Person p) { } // 인자로 Person 타입과 Student 타입 모두 받는 게 가능
  static void downcast2(Student t) { } // 인자로 Student 타입만 받는 게 가능
  ```







