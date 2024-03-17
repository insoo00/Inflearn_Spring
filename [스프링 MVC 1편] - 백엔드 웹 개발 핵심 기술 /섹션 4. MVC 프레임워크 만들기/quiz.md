- 디자인 패턴 중 호환성이 없는 인터페이스 때문에 함께 동작할 수 없는 클래스들을 함께 작동해주도록 변환 역할을 해주는 행동 패턴은?
    - 단일 책임 원칙 (SRP) 충족
    - 개방 폐쇄 원칙 (OCP) 충족

- 서블릿에 대한 종속성을 제거하기 위해 아래와 같이 paramMap을 통해 parameter를 전달했다. 만약 ```username```에 두 개 이상의 값이 존재하는 경우 발생할 수 있는 문제점은 어떤게 있고, 어떻게 사용하는 것이 좋을까?
```username=hello&username=spring```
    ```java
    Map<String, String> paramMap = createParamMap(req);
    ```
