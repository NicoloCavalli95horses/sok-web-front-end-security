# SoK: Web Front-End Security

## Abstract
Web  front-ends  are  the  primary  interface  for  usersto interact with web applications. As with any other softwarecomponent of a web application, ensuring their security duringdevelopment is crucial. While the literature widely studied thesecurity  of  web  applications  in  general,  the  specific  securityaspects of web front-ends remain particularly under explored.This paper proposes the first Systematization of Knowledge(SoK)  on  the  specific  topic  of  web  front-end  security.  Wecompiled  a  corpus  of  54  papers  that  address  this  subject  outof  130  papers  resulting  from  our  search  queries.  This  SoKexhibits  the  following  outcomes:  For  web  front-end  experts,1/  it  identifies  and  details  the  role  of  front-ends  in  the  mostrelevant   web   attacks   and   vulnerabilities,   2/   it   proposes   aclassification of vulnerabilities and their exploitation from thefront-end  viewpoint,  3/  it  analyzes  the  relationships  betweenthese  issues,  describing  both  strong  dependencies  and  weaklinks. This SoK concerns developers of web front-end toolkitsthat  need  a  reference  classification  to  improve  their  toolkits,but it can also serve as a guide for both new and experiencedpractitioners  (e.g.,students,  teachers,  front-end  developers).Finally,  we  outlined  the  main  current  challenges  and  futuredirections  to  build  secured  web  front-ends.

---

# Methodology

Our  research  work  was  guided  by  the  following  researchquestions:

- RQ1. What are the most relevant web vulnerabilities associ-ated with front-ends? What role do front-end function-alities play in this context and how is front-end involvedin a web attack?
- RQ2. What kinds of mitigations, solutions, tools or strategieshave been proposed so far? What are their potentialitiesand their limits?
- RQ3. How are vulnerabilities and attacks related? What kindsof relationships exist between these issues?

We  addressed  these  questions  with  a  systematic,  transparent,  and  repeatable  literature  review

## Keywords used

- Direct   access   to   restricted   resources: ’directorytraversal’, ’forced browsing’, ’path traversal’, ’link fol-lowing’, ’insecure direct object reference’, ’web root’;
- GUI  exploitation:  ’DOM  clobbering’,  ’clickjacking’,’business  flow  tampering’,  ’prototype  pollution’,  ’hid-den  iframe’,  ’invisible  iframe’,  ’hidden  field’,  ’logictampering’;
- Client-side request manipulation: ’tabnabbing’,’CSRF’,  ’redirect  attack’,  ’open  redirect’,  ’parametertampering’, ’confused deputy’;
- Metadatamanipulation:’improperSameSite’,’cookie theft’, ’cookie tampering’, ’session hijacking’,’CORS misconfiguration’, ’JWT tampering’, ’PPI’;
- Insecure  storage:  ’insecure  storage’,  ’localStorage’,’sessionStorage’, ’IndexedDB’, ’web storage’

All the queries and the URLs are available in `data.json`