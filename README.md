# CS305-Project-Two

## Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?
Artemis Financial is a consulting company that works with clients to develop financial plans in areas such as savings, retirement, investments, and insurance. Artemis Financial has tasked us with reviewing their current web application and addressing any potential security vulnerabilities that could pose a risk to both the company and client data. 
## What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?
The value of applying industry standard best practices for secure coding is that we are able to promote data protection and integrity and minimize the risk of security breaches. Maintaining secure coding practices can also help to save time and money by reducing the need to patch vulnerabilities found after release (Ghalleb, 2024). Secure coding can also help us maintain trust with our users by ensuring that their personal information is protected (Ghalleb, 2024). 
## Which part of the vulnerability assessment was challenging or helpful to you?
The most challenging part of the vulnerability assessment was identifying which dependencies were false positives. 
## How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
We increased layers of security by implementing secure communications between the client and web server by adopting HTTPS protocol. 
## How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
After refactoring the application, I ran the application and visited the port in which the web application is running under to check that the application produces the expected output.
## What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
The tool that I think will be helpful in future tasks is the OWASP dependency check plugin which helps to identify vulnerabilities that are introduced by the dependencies used in the project. The vulnerability report produced by the plug in lists the severity of vulnerabilities introduced by a dependency. This will be useful for decision making when deciding which dependencies should need to be addressed. 
## References
Ghalleb, Z. (2024, November 26). What is Secure Coding? Overview and Best Practices. Wiz. https://www.wiz.io/academy/secure-coding-best-practices 

