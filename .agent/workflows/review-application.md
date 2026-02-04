---
description: Application Review
---

Perform a SURGICAL analysis of the APPLICATION layer (src/application). I don't want generalizations; analyze each Use Case:
1. **Single Responsibility**: Does each Use Case do only one thing? Is the orchestration clear?
2. **Dependencies**: Is dependency injection correct? Are there undue couplings with concrete implementations instead of interfaces?
3. **DTOs**: Are DTOs being used correctly to shield the domain? Are there type leaks from the ORM to this layer?
4. **Error Handling**: How are domain exceptions handled and converted here?
List each violation found. For seniority calculation, evaluate the clarity of the data flow and decoupling. Save the exhaustive analysis in ./.reviews/REVIEW_APPLICATION_DDMMYYYY_HH:mm.md.