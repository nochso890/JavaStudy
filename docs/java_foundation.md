# Java Foundation

## Class 기본 및 주석
Java 의 기본 Class 구조 는 아래 와 같다.
````java
class Name{
    /*
        주석을 제외한 모든 코드는 클래스의 Scope{} 내에 작성해야 한다.
    */
}
````
 /* 내용 */ 또는 // 의 경우 주석으로 처리된다.

단 package 및 import 문의 경우 예외로 class 외부에 작성된다.

````java
class Name{
    public static void main(String[] args){ //main 메서드 선언부
        //실행될 문장
    }
}
````

##자바실행과정.
1. 필요한 클래스 들을 로드 한다.
2. 클래스 파일을 검사한다.
3. 지정된 클레스 에서 main 을 호출한다.


#Variable
## 변수.
변수 : 하나의 값을 저장하기 위한 메모리 공간.
변수 초기화 : 변수 사용전 처음으로 값을 저장하는 것.
