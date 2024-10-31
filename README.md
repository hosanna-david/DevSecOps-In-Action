# DevSecOps-in-Action
DevSecOps is the practice of integrating security testing at every stage of the software development process. It includes tools and processes that encourage collaboration between developers, security specialists, and operation teams to build software that is both efficient and secure. 

<div align="center">
<img src="https://github.com/hosanna-david/DevSecOps-in-Action/blob/main/DevSecOps%20in%20Action.jpeg" align="center" style="width: 100%" />
</div>  
<br/>

↳ Secure Code Training --> Equip engineers with essential AppSec principles

↳ Secure by Design --> Adopt threat models and secure-by-default patterns

↳ Pre-commit Scanning & Repo Protection --> Ensure secrets are detected early and access to repositories is secured

↳ CI Security --> Prevent unauthorized pipeline access through role-based access control

↳ Code Analysis --> Automatically scan for vulnerabilities using SAST tools

↳ Composition Analysis --> Ensure open-source libraries comply with security and licensing standards

↳ Automated Deployments --> Use Infrastructure as Code for consistent, secure environments

↳ Security Testing --> Perform DAST to identify runtime vulnerabilities

⤷ Adopting DevSecOps can help mitigate risks and improve security posture as companies transition to cloud-native architectures.


<b>Tools Used for DevSecOps</b><br/>
DevSecOps relies on a variety of tools, categorized under Development, Security, and Operations:

<b>1.Development Tools:</b>

- Git secrets: Git secrets is a tool that helps developers maintain the security of their code repositories.
- Security plugins in Visual Studio Code:Visual Studio Code (VS Code) is a popular code editor that offers security plugins to enhance the security of your development environment.
- Trufflehog:Trufflehog is an open-source security scanning tool used to search for sensitive information within code repositories.

<b>2.Security Tools:</b>

- Code quality tools like SonarQube.
- SAST Security tools such as Fortify, Veracode, and Checkmarx.
- SCA Security tools including Fortify, Veracode, Black Duck, and Snyk.
- DAST Security tools like OWASP ZAP, WebInspect, Veracode DAST, and Acunetix.
- IAC (Infrastructure as Code) security tools such as Synk and Bridgecrew.
- Container security tools like Aqua, Qualys, and Prisma Cloud.

<b>3.Operations Tools:</b>

- Build pipeline tools like GitHub Actions and Jenkins etc.
- Cloud security posture management tools such as Aqua and Bridgecrew.
- Container registry scanning tools like Aqua and AWS Native Registry Scanning.
- Infrastructure scanning tools like Nessus and Chef InSpec (compliance).
- Cloud security tools like AWS Security Hub and Azure Defender.

<b>Basic Security Terms</b>
Before we go further, let’s understand some basic security terms:

- SAST (Static Application Security Testing): This is like scanning a blueprint of a building for security flaws. It checks the code before it’s even run to find vulnerabilities.
- SCA (Software Composition Analysis): Think of this as checking the ingredients of a recipe. SCA looks at the open-source software used in your project to find known vulnerabilities.
- DAST (Dynamic Application Security Testing): This is like testing a house by trying to break in. DAST tests the running application to find weaknesses that might be exploited by attackers.
- IAST (Interactive Application Security Testing): Imagine having security guards inside a building. IAST monitors the application while it’s running and can detect issues in real-time.
- IAC (Infrastructure as Code): This is about securing the setup of your IT infrastructure, like servers and networks, by writing code.
- API Security: Just like securing a door, API security focuses on protecting the interfaces that different software systems use to communicate with each other. It ensures that data is exchanged securely.
These terms help us talk about different aspects of security in software and infrastructure more clearly.

