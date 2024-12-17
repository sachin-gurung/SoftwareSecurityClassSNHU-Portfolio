#### 1. Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?
  The client, Artemis Financial, is a consulting company that creates individualized financial plans, including savings, retirement, investments and insurance. The company wants to modernize its software while ensuring secure communication and data integrity. The main issue was to protect sensitive client data by implementing secure file verification using checksum functionality and ensure data transmission over HTTPS.

#### 2. What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?
  I did well with implementing SHA-256 encryption for secure checksum generation which ensures data integrity. I also enabled secure HTTPS communication using a self-signed SSL certificate to protect transmitted data. Then I did the static analysis using the OWASP dependency-check and resolve vulnerabilities. Secure coding is very important because it protects sensitive data, reduces vulnerabilities that hackers can exploit and ensure software reliability. It adds trust from the clients, reduces financial risks and helps meet regulatory standards.

#### 3. Which part of the vulnerability assessment was challenging or helpful to you?
  Interpreting the dependency-check result was definitely challenging to me. One helpful thing that happened during the course is the hands-on practice that I received while doing my projects. 

#### 4. How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
  I increased layers of security by implementing SHA-256 encryption to verify data integrity with checksum generation, enabled HTTPS protocol with self-signed certificate to ensure secure communication and conducted static vulnerability testing using OWASP dependency-check and resolve security risks. In the future, I'd definitely use all these techniques to make my software more secure.

#### 5. How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
  I knew that my cod3e and software application were functional and secure because my refactored code was executed successfully without syntax or logical errors. I tested checksum endpoint '/hash' to confirm it generated accurate SHA-256 hashes and also converted HTTP to HTTPS verifying secure communication. After refactoring the code, I used OWASP dependency-check to ensure no new vulnerabilities were introduced.

#### 6. What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
  Some of the tools, resources and coding practices that can be helpful in future tasks are the SHA-256 encryption for data verification, generating self-signed certificates for HTTPS communication using Java Keytool, OWASP dependency-check to identify vulnerabilities and writing error free logical code. 

#### 7. Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
  For my future employers, I can show that I can successfully implement secure communication using SHA-256 encryption and HTTPS, use OWASP dependency-check for static vulnerability testing and refactor code successfully.
