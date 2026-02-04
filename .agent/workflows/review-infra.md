---
description: Infra Review
---

Perform a detailed TECHNICAL audit of the INFRASTRUCTURE layer (src/infra). Go deep into the implementation:
1. **Repositories**: Analyze the implementation of the methods. Is the use of the ORM/Database (e.g., Prisma) optimized? Are there any visible N+1 problems or inefficient queries?
2. **Mappers**: Is the conversion between the persistence model and the domain entity isolated and correct?
3. **Tests**: Check if there are mocks or in-memory implementations (test repositories) and if they faithfully reflect the expected behavior.
4. **External Dependencies**: How are third-party libraries managed here?
Don't skimp on technical criticism. I want every "code smell" listed. Base the seniority estimate on the domain of tools and persistence patterns. Save in ./.reviews/REVIEW_INFRA_DDMMYYYY_HH:mm.md.