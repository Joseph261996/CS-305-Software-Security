# CS-305 Software Security

## Artemis Financial Project

### Client and Software Requirements

Artemis Financial is a consulting company that develops individualized financial plans for its customers, including savings, retirement, investments, and insurance. The company wanted to modernize its software and improve the security of its public web interface. The main issue I addressed was protecting sensitive financial information and ensuring secure communications when data was transferred through the application. I added a checksum verification process, HTTPS secure communication, and other security improvements to the application.

### Finding and Addressing Software Security Vulnerabilities

I did well at identifying vulnerabilities by using manual code review and the OWASP Dependency-Check tool. The dependency scan helped identify vulnerable third-party dependencies that needed attention. Secure coding is important because vulnerabilities can expose sensitive information, allow unauthorized access, or negatively affect a company's reputation. Strong software security helps protect customers, maintain trust, reduce risk, and support the overall well-being of a company.

### Challenging and Helpful Parts of the Vulnerability Assessment

One of the most challenging parts was understanding the large number of vulnerabilities reported by the dependency-check tool and determining which issues were related to the application's dependencies. The process was also helpful because it showed me how automated security testing can identify problems that may not be obvious during a manual code review.

### Increasing Layers of Security

I increased the application's layers of security by implementing a cryptographic hash and checksum verification, generating a self-signed certificate, and configuring the application to use HTTPS instead of HTTP. I also used dependency-check to identify security vulnerabilities in the application's dependencies. In the future, I would continue using automated tools such as dependency scanners along with manual code reviews and security testing to assess vulnerabilities and determine appropriate mitigation techniques.

### Functional and Security Testing

I made sure the application remained functional by compiling and running the application after making the security changes. I verified that the HTTPS server started on port 8443 and tested the application through the secure HTTPS endpoint. I also used OWASP Dependency-Check as a secondary static testing tool after refactoring the application to check whether additional vulnerabilities had been introduced.

### Resources, Tools, and Coding Practices

The resources and tools I used included Java, Spring Boot, Maven, Java Keytool, Eclipse, OWASP Dependency-Check, and secure HTTPS communication. I also used cryptographic hashing and checksum verification as part of the security improvements. These tools and practices will be useful in future software development and cybersecurity assignments because they provide ways to identify vulnerabilities, protect communications, and verify the security of an application.

### Work I Would Show Future Employers

I would show future employers the completed Artemis Financial Practices for Secure Software Report because it demonstrates my ability to identify vulnerabilities, apply secure coding practices, implement encryption and secure communications, perform security testing, and document the security improvements I made. This project demonstrates practical experience with Java, Spring Boot, Maven, HTTPS, certificates, cryptographic hashing, and vulnerability assessment.
