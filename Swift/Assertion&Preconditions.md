# Assertion & Preconditions
- Assertion과 Preconditions는 런타임 시 발생하는 상황을 체크한다.
- 코드가 진행되기 전에 필수적인 조건이 안전한지 검사하기 위해 사용된다.
- true를 반환하면 코드가 계속 진행되고 false가 반환되면 코드는 멈추고 앱이 종료된다.
- Assertion은 개벌 중 잘못된 예측을 잡아내는데, Preconditions은 제품화된 앱에서 문제를 감지하는데 사용할 수 있다.
- try~catch와는 달리 복구 가능하거나 예측 가능한 에러를 처리하는데는 사용할 수 없다.