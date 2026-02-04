---
description: Presentation Review
---

Analyze the PRESENTATION layer (src/presentation) line by line. Focus entirely on the HTTP/API interface:
1. **Controllers**: Are they "lean"? Do they only receive requests, call the Use Case and return responses, or are they containing business rules (which would be a serious error)?
2. **Validation and DTOs**: Is the input data validation robust? Are errors returned with semantically correct HTTP status codes (400, 401, 404, 500)?
3. **Framework (Elysia)**: Is the framework being used following best practices or are there "hacks"?
4. **Routes**: Is the route definition organized and RESTful?
Point out each inconsistency in the API. Seniority here should be measured by knowledge of Web/HTTP standards and cleanliness of the input code. Save the detailed report in ./.reviews/REVIEW_PRESENTATION_DDMMYYYY_HH:mm.md.