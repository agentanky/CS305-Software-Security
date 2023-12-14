# CS305-Software-Security


# Summary of Artemis Financial and Their Software Requirements
Artemis Financial, a client in the financial services sector, approached us with the need to enhance the security of their complex web application developed using the Spring Framework. Their primary requirement was to incorporate an expressive command input function while ensuring the application remains secure against potential vulnerabilities. The focus was on safeguarding sensitive financial data and maintaining robust user authentication and authorization mechanisms.

# Addressing Artemis Financial's Issues and Excellence in Vulnerability Identification
When addressing the client's software security vulnerabilities, one of the key strengths was the thoroughness of the manual code review process. This involved a meticulous examination of the application's authentication and authorization mechanisms, data security practices, input validation processes, session management, error handling, and auditing/logging procedures. The identification of vulnerabilities was not just surface-level but delved deep into the intricacies of the Spring Framework and its dependencies, especially considering the known vulnerabilities in the specific version of spring-data-rest-webmvc.

# Importance and Value of Secure Coding
Secure coding is of paramount importance, especially in the financial sector where data breaches can have severe consequences, including financial loss, reputational damage, and legal repercussions. By coding securely, we added significant value to Artemis Financial's overall wellbeing by protecting sensitive financial data, ensuring compliance with financial regulations and standards, and building trust with customers who rely on the integrity and confidentiality of their financial transactions and data.

# Challenges and Helpful Aspects of the Vulnerability Assessment
One of the most challenging aspects of the vulnerability assessment was keeping up-to-date with the latest security threats and ensuring that every aspect of the application, including third-party libraries and frameworks, was scrutinized. However, this was also helpful as it provided a comprehensive view of the application's security posture, revealing areas that needed improvement beyond the immediate scope of the project.

# Increasing Layers of Security and Future Strategies for Vulnerability Assessment
To increase layers of security, the application was enhanced with more robust authentication mechanisms, stringent authorization checks, encrypted data storage and transmission, rigorous input validation, secure session management, and improved error handling. For future vulnerability assessments, using tools like static and dynamic code analysis software, and keeping abreast of the latest entries in vulnerability databases like CVE and NVD, will be crucial in deciding which mitigation techniques to apply.

# Ensuring Functional and Secure Code and Post-Refactoring Checks
To ensure that the code and software application were both functional and secure, we employed a combination of automated and manual testing strategies, including unit testing, integration testing, and security-specific testing like penetration testing. After refactoring the code, re-running these tests and conducting additional code reviews helped in verifying that no new vulnerabilities were introduced.

# Resources, Tools, and Practices for Future Assignments
During this assignment, several resources, tools, and coding practices proved invaluable and would be beneficial for future tasks. These include:

# Static and dynamic analysis tools for identifying vulnerabilities.
The OWASP Top 10 and CWE/SANS Top 25 lists for staying aware of common security pitfalls.
Secure coding guidelines, specifically for Java and the Spring Framework.
Automated testing tools to validate both functionality and security post-refactoring.
Demonstrable Work for Future Employers
For future employers, demonstrable work from this assignment includes:

# Detailed reports documenting the identified vulnerabilities and the rationale behind chosen mitigation strategies.
Code snippets or commit histories showing the before-and-after states of security enhancements.
Test results and security audit reports that illustrate the effectiveness of the implemented security measures.
A case study or summary explaining the approach, challenges, and successes of this project, highlighting key learning points and how they were applied to enhance the security of Artemis Financial's application.
