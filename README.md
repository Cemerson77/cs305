**# cs305**

**Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?**

As a developer for GlobalRain, I was a member of the agile scrum team on projects gathered in this repository. In my role at Global Rain, I worked with Artemis Financial, which develops individualized financial plans for its clients. Modernizing Artemis Financial's operations was a priority. For their custom software to be successful, they also needed the most current and effective software security. Artemis Finacial needed to protect the organization from external threats. In addition, ways to protect their client data and financial information. To ensure secure communications, I added a file verification step to their web application. Data verification was required when the web application transferred data using a checksum. I had to take their current software application and add secure communication mechanisms to meet their software security requirements. 

**What did you do very well when you found your client's software security vulnerabilities? Why is it important to code securely? What value does software security add to a company's overall wellbeing?**

I did excellent in static testing; I successfully identified current vulnerabilities in the code base. A secure coding strategy is crucial to preventing data theft and safeguarding a company's reputation for reliability and integrity. The first step in developing a secure implementation strategy for Artemis Financial was identifying security vulnerabilities. Once these vulnerabilities were identified, integrating industry best practices and solutions were the most beneficial action. Software security does not need to be reinvented. In this way, any problems may already have been identified and fixed if you use accepted libraries and dependencies.

**What part of the vulnerability assessment was challenging or helpful to you?**

Instead of checking each dependency manually for vulnerabilities, the dependency check tool saved a lot of time by detecting vulnerabilities automatically.

**How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?**

To make the code more secure, I refactored it to incorporate HTTPS. Depending on the current security situation, I would probably follow whichever process is most secure at that time. However, a CA certificate would be preferable to a self-signed one. Additionally, I will continue using the dependency checker.

**How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?**

When new dependencies were added, the dependency check had to be rerun. Alternatively, manual code review and unit testing can verify functionality.

**What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?**

The Internet was beneficial to me in researching current practices and algorithms. In addition, the Maven tools were invaluable in detecting the vulnerabilities and will continue to be helpful.

**Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?**

I would show future employers the static testing and research I did to complete the projects. In addition, my experience with suppressing false positives, identifying and fixing vulnerabilities, and creating a secure HTTP application.
