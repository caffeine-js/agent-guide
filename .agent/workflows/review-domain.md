---
description: Domain Review
---

Perform a THOROUGH and CRITICAL analysis, file by file, of the DOMAIN layer (src/domain) of this project. Do not summarize. I want you to validate the purity of the domain:
1. **Entities and Value Objects**: Check for leaks of infrastructure logic or frameworks. Is the encapsulation correct? Are the types rich and expressive?
2. **Interfaces/Contracts**: Do the repository interfaces respect the SOLID principle (especially ISP and DIP)? Are they database-agnostic?
3. **Business Rules**: Identify if all essential business rules are here or if they have been incorrectly delegated to other layers.
List ALL strengths and WEAKNESSES with code examples. Estimate the level of seniority demonstrated ONLY in this layer. Save the output to the file ./.reviews/REVIEW_DOMAIN_DDMMYYYY_HH:mm.md, referring to previous reviews for context.