# SoK: Web Front-End Security

## Abstract
Web front-ends are the primary interface for users to interact with web applications. As with any other software component of a web application, ensuring their security during development is crucial. While the literature widely studied the security of web applications in general, the specific security aspects of web front-ends remain particularly under explored. This paper proposes the first Systematization of Knowledge (SoK) on the specific topic of web front-end security. We compiled a corpus of 54 papers that address this subject out of 130 papers resulting from our search queries. This SoK exhibits the following outcomes: For web front-end experts, 1/ it identifies and details the role of front-ends in the most relevant web attacks and vulnerabilities, 2/ it proposes a classification of vulnerabilities and their exploitation from the front-end viewpoint, 3/ it analyzes the relationships between these issues, describing both strong dependencies and weak links. This SoK concerns developers of web front-end toolkits that need a reference classification to improve their toolkits, but it can also serve as a guide for both new and experienced practitioners (e.g., students, teachers, front-end developers). Finally, we outlined the main current challenges and future directions to build secured web front-ends.

---

# Methodology

Our research work was guided by the following research questions:

- RQ1. What are the most relevant web vulnerabilities associated with front-ends? What role do front-end functionalities play in this context and how is front-end involved in a web attack?
- RQ2. What kinds of mitigations, solutions, tools or strategies have been proposed so far? What are their potentialities and their limits?
- RQ3. How are vulnerabilities and attacks related? What kinds of relationships exist between these issues?

We addressed these questions with a systematic, transparent, and repeatable literature review

## Keywords used

- Direct access to restricted resources: ’directory traversal’, ’forced browsing’, ’path traversal’, ’link following’, ’insecure direct object reference’, ’web root’;
- GUI exploitation: ’DOM  clobbering’, ’clickjacking’, ’business  flow  tampering’, ’prototype  pollution’, ’hidden  iframe’,  ’invisible  iframe’,  ’hidden  field’,  ’logic tampering’;
- Client-side request manipulation: ’tabnabbing’, ’CSRF’, ’redirect  attack’, ’open redirect’, ’parameter tampering’, ’confused deputy’;
- Metadata manipulation: ’improper SameSite’, ’cookie theft’, ’cookie tampering’, ’session hijacking’, ’CORS misconfiguration’, ’JWT tampering’, ’PPI’;
- Insecure storage: ’insecure storage’, ’localStorage’, ’sessionStorage’, ’IndexedDB’, ’web storage’

All the queries and the URLs are available in `data.json`

The distribution of papers by year and the number of papers addressing each vulnerability and attack discussed in our SoK, can be found in the `charts` folder
