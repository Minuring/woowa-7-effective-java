## [Effective Java 스터디]

### 일정
25.02.24. ~ 25.04.04 (레벨 1 기간)

### 목록

- [x] 1. [생성자 대신 정적 팩터리 메서드를 고려하라](./02장/1_생성자_대신_정적_팩터리_메서드를_고려하라.md)- 젠슨 
- [x] 2. [생성자에 매개변수가 많다면 빌더를 고려하라](./02장/2_생성자에_매개변수가_많다면_빌더를_고려하라.md) - 젠슨
- [x] 3. [private 생성자나 열거 타입으로 싱글턴임을 보증하라](./02장/3_인스턴스화를_막기_위한_private_생성자.md) - 돔푸
- [x] 4. [인스턴스화를 막으려거든 private 생성자를 사용하라](./02장/4_인스턴스화를_막기_위한_private_생성자.md) - 돔푸
- [x] 5. [자원을 직접 명시하지 말고 의존 객체 주입을 사용하라](./02장/5_자원을_직접_명시하지_말고_의존_객체_주입을_사용하라.md) - 포라
- [x] 6. [불필요한 객체 생성을 피하라](/02장/6_불필요한_객체_생성을_피하라.md) - 포라
- [x] 7. [다 쓴 객체 참조를 해제하라](./02장/7_다_쓴_객체_참조를_해제하라.md) - 포라
- [ ] 8. finalizer와 cleaner 사용을 피하라
- [ ] 9. try-finally보다는 try-with-resources를 사용하라
- [x] 10. [equals는 일반 규약을 지켜 재정의하라](./03장/10_equals는_일반_규약을_지켜_재정의하라.md) - 포라
- [ ] 11. equals를 재정의하려거든 hashCode도 재정의하라
- [ ] 12. toString을 항상 재정의하라
- [ ] 13. clone 재정의는 주의해서 진행하라
- [ ] 14. Comparable을 구현할지 고려하라
- [x] 15. [클래스와 멤버의 접근 권한을 최소화하라](./04장/15_클래스와_멤버의_접근_권한을_최소화하라.md) - 포라
- [x] 16. [public 클래스에서는 public 필드가 아닌 접근자 메서드를 사용하라](./04장/16_public_클래스에서는_public_필드가_아닌_접근자_메서드를_사용하라.md) - 포라
- [x] 17. [변경 가능성을 최소화하라](./04장/17_변경_가능성을_최소화_해라.md) - 젠슨
- [ ] 18. 상속보다는 컴포지션을 사용하라
- [ ] 19. 상속을 고려해 설계하고 문서화하라. 그러지 않았다면 상속을 금지하라.
- [x] 20. [추상 클래스보다는 인터페이스를 우선하라](./04장/20_추상_클래스보다는_인터페이스를_우선하라라.md) - 가이온
- [x] 21. [인터페이스는 구현하는 쪽을 생각해 설계하라](./04장/21_인터페이스는_구현하는_쪽을_생각해_설계하라.md) - 포라
- [x] 22. [인터페이스는 타입을 정의하는 용도로만 사용하라](./04장/22_인터페이스는_타입을_정의하는_용도로만_사용하라.md) - 포라
- [ ] 23. 태그 달린 클래스보다는 클래스 계층구조를 활용하라
- [x] 24. [멤버 클래스는 되도록 static으로 만들라](./04장/24_멤버_클래스는_되도록_static으로_만들라.md) - 가이온
- [ ] 25. 톱레벨 클래스는 한 파일에 하나만 담으라
- [ ] 26. 로 타입은 사용하지 말라
- [ ] 27. 비검사 경고를 제거하라
- [ ] 28. 배열보다는 리스트를 사용하라
- [ ] 29. 이왕이면 제네릭 타입으로 만들라
- [ ] 30. 이왕이면 제네릭 메서드로 만들라
- [ ] 31. 한정적 와일드카드를 사용해 API 유연성을 높이라
- [ ] 32. 제네릭과 가변인수를 함께 쓸 때는 신중하라
- [ ] 33. 타입 안전 이종 컨테이너를 고려하라
- [ ] 34. int 상수 대신 열거 타입을 사용하라
- [x] 35. [ordinal 메서드 대신 인스턴스 필드를 사용하라](./06장/35_ordinal_대신_필드를_사용하라.md) - 돔푸
- [x] 36. [비트 필드 대신 EnumSet을 사용하라](./06장/36_EnumSet을_사용하라.md) - 돔푸
- [x] 37. [ordinal 인덱싱 대신 EnumMap을 사용하라](./06장/37_EnumMap을_사용하라.md) - 돔푸
- [x] 38. [확장할 수 있는 열거 타입이 필요하면 인터페이스를 사용하라](./06장/38_확장할%20_수_있는_열거형이_필요하면_인터페이스를_사용하라.md) - 돔푸
- [ ] 39. 명명 패턴보다 애너테이션을 사용하라
- [ ] 40. @Override 애너테이션을 일관되게 사용하라
- [ ] 41. 정의하려는 것이 타입이라면 마커 인터페이스를 사용하라
- [x] 42. [익명 클래스보다는 람다를 사용하라](.07장/42_익명_클래스보다는_람다를_사용하라.md) - 가이온
- [x] 43. [람다보다는 메서드 참조를 사용하라](.07장/43_람다보다는_메서드_참조를_사용하라.md) - 가이온
- [ ] 44. 표준 함수형 인터페이스를 사용하라
- [ ] 45. 스트림은 주의해서 사용하라
- [ ] 46. 스트림에서는 부작용 없는 함수를 사용하라
- [ ] 47. 반환 타입으로는 스트림보다 컬렉션이 낫다
- [ ] 48. 스트림 병렬화는 주의해서 적용하라
- [ ] 49. 매개변수가 유효한지 검사하라
- [x] 50. [적시에 방어적 복사본을 만들라](./08장/50_적시에_방어적_복사본을_만들라.md) - 젠슨
- [ ] 51. 메서드 시그니처를 신중히 설계하라
- [ ] 52. 다중정의는 신중히 사용하라
- [ ] 53. 가변인수는 신중히 사용하라
- [x] 54. [null이 아닌, 빈 컬렉션이나 배열을 반환하라](./08장/54_null_이_아닌_빈_컬렉션이나_배열을_반환하라.md) - 가이온
- [x] 55. [옵셔널 반환은 신중히 하라](./08장/55_옵셔널_반환은_신중히_하라.md) - 가이온
- [ ] 56. 공개된 API 요소에는 항상 문서화 주석을 작성하라
- [ ] 57. 지역변수의 범위를 최소화하라
- [ ] 58. 전통적인 for 문보다는 for-each 문을 사용하라
- [ ] 59. 라이브러리를 익히고 사용하라
- [ ] 60. 정확한 답이 필요하다면 float와 double은 피하라
- [ ] 61. 박싱된 기본 타입보다는 기본 타입을 사용하라
- [ ] 62. 다른 타입이 적절하다면 문자열 사용을 피하라
- [ ] 63. 문자열 연결은 느리니 주의하라
- [ ] 64. 객체는 인터페이스를 사용해 참조하라
- [ ] 65. 리플렉션보다는 인터페이스를 사용하라
- [ ] 66. 네이티브 메서드는 신중히 사용하라
- [ ] 67. 최적화는 신중히 하라
- [ ] 68. 일반적으로 통용되는 명명 규칙을 따르라
- [x] 69. [예외는 진짜 예외 상황에만 사용하라](./10장/69_예외는_진짜_예외_상황에만_사용하라.md) - 젠슨
- [x] 70. [복구할 수 있는 상황에는 검사 예외를, 프로그래밍 오류에는 런타임 예외를 사용하라](./10장/.10장/69_예외는_진짜_예외_상황에만_사용하라.md) - 젠슨
- [x] 71. [필요 없는 검사 예외 사용은 피하라](./10장/71_필요_없는_검사_예외_사용은_피하라.md) - 젠슨
- [x] 72. [표준 예외를 사용하라](./10장/72_표준_예외를_사용하라.md) - 젠슨
- [x] 73. [추상화 수준에 맞는 예외를 던지라](./10장/73_추상화_수준에_맞는_예외를_던져라.md) - 돔푸
- [ ] 74. 메서드가 던지는 모든 예외를 문서화하라
- [x] 75. [예외의 상세 메시지에 실패 관련 정보를 담으라](./10장/75_예외의_상세_메시지에_실패_관련_정보를_담으라.md) - 돔푸
- [ ] 76. 가능한 한 실패 원자적으로 만들라
- [ ] 77. 예외를 무시하지 말라
- [ ] 78. 공유 중인 가변 데이터는 동기화해 사용하라
- [ ] 79. 과도한 동기화는 피하라
- [ ] 80. 스레드보다는 실행자, 태스크, 스트림을 애용하라
- [ ] 81. wait와 notify보다는 동시성 유틸리티를 애용하라
- [ ] 82. 스레드 안전성 수준을 문서화하라
- [ ] 83. 지연 초기화는 신중히 사용하라
- [ ] 84. 프로그램의 동작을 스레드 스케줄러에 기대지 말라
- [ ] 85. 자바 직렬화의 대안을 찾으라
- [ ] 86. Serializable을 구현할지는 신중히 결정하라
- [ ] 87. 커스텀 직렬화 형태를 고려해보라
- [ ] 88. readObject 메서드는 방어적으로 작성하라
- [ ] 89. 인스턴스 수를 통제해야 한다면 readResolve보다는 열거 타입을 사용하라
- [ ] 90. 직렬화된 인스턴스 대신 직렬화 프록시 사용을 검토하라

### 학습 목적
- 이펙티브 자바는 레벨 1 필독서 중 하나로, 효율적인 자바 코드를 짜기 위한 솔루션들을 배울 수 있는 책입니다. 하지만 책의 모든 아이템을 정독하면서 테스트 해보고, 책의 예제 외에 적용할 수 있는 코드를 작성해 보는 것을 레벨 1 동안 혼자서 마치기란 쉽지 않습니다. 따라서 여러 사람이 함께 스터디하여 학습 효율을 높이고 레벨 1 동안 완독하는 것을 목표로 합니다.
- 개인적으로 효과적인 학습 방식 중 하나가 본인이 배운 내용을 남에게 설명하거나 가르쳐주는 것이라고 생각합니다. 자신이 맡은 아이템에 대해 발표함으로써 해당 아이템에 대해 효과적으로 학습할 수 있습니다.
- 또한 맡은 아이템이 아니더라도 책을 읽으면서 이해가 가지 않는 부분에 대해 의문점을 가져보고, 다른 크루들과의 토론으로 의문을 풀어나가는 과정을 통해 효율적인 학습을 추구하고자 합니다.

### 진행 방식
- 매주 월, 금 19시에 스터디를 진행합니다.
- 매 스터디마다 1인당 이펙티브 자바의 2개 아이템에 대한 20분 이내의 발표를 진행합니다.
  - 발표자료의 형식은 자유입니다.
- 질문 사항에 대해 발표자가 잘 모르겠다면, Q&A 기간내에 추후 답변도 가능합니다.
- 본인이 발표하지 않는 아이템도 반드시 읽고 이해가 되지 않는 부분에 대해 질문해주시면 됩니다.

스터디 전까지 정리한 내용을 pr 올려주세요.
