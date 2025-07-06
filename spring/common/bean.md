# Bean
- 노션 페이지
  - https://www.notion.so/Bean-22637112afc78042b603fba9656a7cbd
## @Component, @Bean의 차이

**등장 배경**

- component
    - XML <bean> class 등록의 번거로움 제거
- bean
    - XML factory-method 패턴의 복잡성 제거

Bean은 객체인데

component는 new Class를 spring에서 해주도록 되어있고

configuration의 bean은 개발자가 직접 만들어 리턴하는 객체를 bean으로 등록하는 것

## 빈 등록과정 공식문서 링크

component, bean, configuration 어노테이션으로 빈 등록되는 과정을 알아봤고 이를 확인해줄 링크 아래에 첨부

- https://docs.spring.io/spring-framework/reference/core/beans/classpath-scanning.html?utm_source=chatgpt.com
- https://docs.spring.io/spring-framework/reference/core/beans/java/bean-annotation.html?utm_source=chatgpt.com

## 