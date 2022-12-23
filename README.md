# interview

### 질문 받았던 내용을 학습하고 정리 하는 저장소

#### 질문 목록

- **CheckedException** vs **UncheckedException**의 차이점

  - Spring `@Transaction`에서 **CheckedException**과 **UncheckedException** 중 **Rollback** 대상은?

  > [CheckedException vs UncheckedException & @Transactional Rollback Rules](https://github.com/sedin2/CS-Study/blob/main/Java/checked-exception-vs-unchecked-exception.md)

- **Primitive Type** vs **Wrapper Class**

  - Method Signature에 Parameter가 두 가지 있었는데 하나는 **primitive** type의 long을, 나머지는 **wrapper** 클래스 Long을 받았는데 둘의 차이를 설명 해 주세요.
  ```java
  // Ex)
  public responseDto getInterest(long userId, Long accountId) {
    ...
  }
  ```
  > [Java Primitive Type vs Wrapper Class](https://github.com/sedin2/CS-Study/blob/main/Java/primitive-vs-wrapper.md)