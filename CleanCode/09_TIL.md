# :pencil: TIL (2022-03-06)
## DAY 9
:book: 오늘 읽은 범위 : ~ 9장(단위 테스트)
---
> :heart_eyes: **책에서 기억하고 싶은 내용을 써보세요.** :clap:
- (_p.157_) 테스트는 유연성, 유지보수성, 재사용성을 제공한다. 테스트 코드를 깨끗하게 유지하지 않으면 결국은 잃어버린다.


- (_p.164_) [테스트 당 assert 하나] assert 문이 하나인 함수는 결론이 하나라서 코드를 이해하기 쉽고 빠르다
  (...) assert 문을 여럿 사용하는 편이 좋다고 생각한다.(...) 때로는 주저 없이 함수 하나에 여러 assert 문을
넣기도 한다. __단지 assert 문 개수는 최대한 줄여야 좋다는 생각이다__


- (_p.166_) [테스트 당 개념 하나] (...) 가장 좋은 규칙은 __"개념 당 assert 문 수를 최소로 줄여라"와 테스트 함수 하나는 개념 하나만 테스트하라"__ 라 하겠다.
 

- (_p.168_) [결론] 테스트 코드는 실제 코드만큼이나 프로젝트 건강에 중요하다. 어쩌면 실제 코드보다 더 중요할지도 모르겠다.
테스트 코드는 실제 코드의 유연성, 유지보수성, 재사용성을 보존하고 강화하기 떄문이다. 그러므로 테스트 코드는 지속적으로 깨끗하게 관리하자.


> :thinking: **오늘 읽은 소감은? 떠오르는 생각을 가볍게 적어보세요**
- 테스트 코드의 중요도를 다시한번 생각했다.
- 테스트 코드의 주제는 별도의 책 한권 이상의 분량을 할애해도 모자라는 분야라는 점을 알게 되었다.

> :mag_right: **궁금한 내용이 있거나, 잘 이해되지 않는 내용이 있다면 적어보세요.**  

[__BUILD-OPERATE-CHECK 패턴__]  
- (1) 테스트 자료를 만든다.
- (2) 테스트 자료를 조작한다.
- (3) 조작한 결과가 올바른지 확인한다.  

[TEMPLATE METHOD 패턴](https://ko.wikipedia.org/wiki/%ED%85%9C%ED%94%8C%EB%A6%BF_%EB%A9%94%EC%86%8C%EB%93%9C_%ED%8C%A8%ED%84%B4)
  
[F.I.R.S.T]
- (1) 빠르게(Fast): 테스트는 빨라야한다.
- (2) 독립적으로(Independent): 각 테스트는 서로 의존하면 안 된다.
- (3) 반복가능하게(Repeatable): 테스트는 어떤 환경에서도 반복 가능해야 한다.
- (4) 자가검증하는(Self-Validating): 테스트는 부울(bool)값으로 결과를 내야 한다. 성공 아니면 실패다.
- (5) 적시에(Timely): 테스트는 적시에 작성해야 한다.
