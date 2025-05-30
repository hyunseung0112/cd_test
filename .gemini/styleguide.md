# 팬마음 Android Gemini 스타일 가이드
* **언어:** 모든 리뷰는 한국어로 작성되어야 합니다.

# 핵심 원칙
* **가독성:** 모든 팀원이 코드를 쉽게 이해할 수 있어야 합니다..
* **유지보수성:** 코드는 수정 및 확장이 용이해야 합니다.
* **일관성:** 모든 프로젝트에서 일관된 스타일을 유지하면 협업이 원활해지고 오류가 줄어듭니다.
* **성능:** 가독성이 가장 중요하지만, 코드가 효율적으로 동작해야 합니다.

## 네이밍 컨벤션
* **변수:** 소문자와 대문자를 조합한 카멜 케이스(CamelCase) 사용: `userName`, `totalCount`
* **상수:** 대문자와 밑줄(_) 조합 사용: `MAX_VALUE`, `DATABASE_NAME`
* **함수:** 소문자와 대문자를 조합한 카멜 케이스(CamelCase) 사용: `calculateTotal()`, `processData()`
* **클래스:** 카멜 케이스(CamelCase) 사용: `UserManager`, `PaymentProcessor`

# 도구
* **Linter:** Ktlint를 사용합니다.
