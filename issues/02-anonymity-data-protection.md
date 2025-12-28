# Ensuring User Anonymity and Data Protection

**Discussion topic:** Best practices for anonymising user data and handling re‑identification risks, especially in social media datasets that can contain rich contextual information.

## Key Questions
, What constitutes effective de‑identification for social media data? (e.g., removing usernames, profile URLs, geotags)
, How can we assess the risk of re‑identification from seemingly innocuous attributes (e.g., rare job titles, unique life events)?
, What additional safeguards (aggregation, perturbation, differential privacy) are appropriate for different types of analysis?
, How should we handle multimedia content (profile pictures, shared images) that may identify individuals even when text is anonymised?
, What are the ethical and legal requirements for storing, sharing, and retaining social media data?

## Potential Guidelines
, **De‑identification checklist:** Remove all direct identifiers (usernames, profile URLs, email addresses, phone numbers). Pseudonymise user IDs with a secure hash.
, **Contextual anonymisation:** Consider that indirect identifiers (location, workplace, hobbies) can together re‑identify users. Use techniques such as k‑anonymity, l‑diversity, or differential privacy for sensitive datasets.
, **Multimedia content:** If images or videos are essential to the research, ensure that faces and other identifiable features are blurred or removed, or obtain explicit consent for their use.
, **Data storage:** Encrypt datasets at rest, restrict access to authorised personnel, and define a clear retention schedule (delete raw data after a fixed period or after project completion).
, **Data sharing:** When sharing anonymised datasets with other researchers, provide a data‑use agreement and ensure that the recipient understands the re‑identification risks.

## References
- [ETHICAL_FRAMEWORK.md](../ETHICAL_FRAMEWORK.md) – Section 2. Anonymity and Privacy
- [Researcher checklist](../templates/researcher_checklist.md) – Includes anonymisation steps

*This document is a starting point for discussion. Please add comments, suggestions, or examples from your own research.*