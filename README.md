# cs-305
CS305

1. Briefly summarize your client, Artemis Financial, and its software requirements.
Artemis Financial is a financial services company that needed a secure web application to handle sensitive customer data and financial transactions. They wanted me to find and fix vulnerabilities that could lead to data leaks, unauthorized access, and cyberattacks. They also needed compliance with regulations like GDPR and PCI-DSS.

2. What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?
I conducted a full manual code review and a static analysis using dependency-check tools. I was able to find hardcoded credentials, SQL injection risks, missing authentication, and outdated cryptographic libraries. Coding securely is critical because it protects customer trust, prevents data breaches, and shields the company from legal and financial losses. Good security makes a business more stable and trustworthy.

3. Which part of the vulnerability assessment was challenging or helpful to you?
The most challenging part was finding vulnerabilities tied to third-party libraries during static testing. It’s tricky because a lot of problems hide behind dependencies. However, it was helpful because it taught me how dangerous outdated libraries can be, even if my own code is clean.

4. How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
I added layers of security by recommending encryption for data at rest and in transit, input validation, strong authentication (JWT/OAuth), and proper role-based access control. In the future, I would continue using static code analysis tools like OWASP Dependency-Check, integrate security into CI/CD pipelines, and prioritize fixes based on CVSS scores and business impact.

5. How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
I tested the application after refactoring by validating user inputs, checking encryption protocols, and re-running static vulnerability scans. I made sure there were no critical findings after changes, and I kept an eye on whether new warnings appeared in the dependency report.

6. What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
I used OWASP Dependency-Check, manual code inspection techniques, best practices from OWASP Top Ten, and secure coding guidelines like using prepared statements, encrypted connections, and structured logging. These tools and habits will definitely help me in securing future projects.

7. Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
I would show employers the completed Artemis Financial Vulnerability Assessment Report, the static analysis results, and the documented mitigation plan. It proves I can identify risks, prioritize fixes, and improve software security with real-world methods.
