# Application of Static Application Security Testing (SAST) Tools

Web applications have become an incredibly important part of our daily lives due to their extensive and ever-increasing consumption. As a result of the large number of users linked with online applications, the current environment has seen them become increasingly susceptible. Hackers aim to seize web applications in order to procure personal information from consumers. Unfortunately, most web applications are vulnerable to attackers because their source code is improperly structured and written. Developers must create secure web apps by avoiding security flaws. The primary objective of this document is to provide a concise description of static code analysis, its attributes, and prospects, as well as an overview of the constructs and technologies that underpin this type of software development approach, as well as the tools that enable software developers to use code reviewing tools to assist in the development of applications, allowing them to optimize the code and rectify blunders before it is executed. For the case study, I have evaluated the source code of http://demo.testfire.net/.

Source code analysis tools, commonly known as Static Application Security Testing (SAST) tools, can assist uncover security problems by analyzing source code or developed versions of code. SAST tools can be integrated into your IDE. Such technologies can aid in the detection of flaws in software development. When opposed to uncovering vulnerabilities later in the development cycle, SAST tool feedback can save time and effort. 


## Vulnerabilities Screenshot

![](https://user-images.githubusercontent.com/71205815/147677551-93772156-d3ff-4ca7-92b0-34375a1ba849.jpg)

![](https://user-images.githubusercontent.com/71205815/147677661-8aa70818-0449-44c7-9ea3-81a64db27612.png)

## SonarQube

SonarQube is a Code Quality Assurance tool that collects and analyzes source code, and provides reports for the code quality of your project. It combines static and dynamic analysis tools and enables quality to be measured continually over time. Everything from minor styling choices, to design errors are inspected and evaluated by SonarQube. This provides users with a rich searchable history of the code to analyze where the code is messing up and determine whether or not it is styling issues, code defeats, code duplication, lack of test coverage, or excessively complex code. The software will analyze source code from different aspects and drills down the code layer by layer, moving module level down to the class level, with each level producing metric values and statistics that should reveal problematic areas in the source code that needs improvement.

Sonarqube also ensures code reliability, Application security, and reduces technical debt by making your code base clean and maintainable. Sonarqube also provides support for 27 different languages, including C, C++, Java, Javascript, PHP, GO, Python, and much more.SonarQube also provides Ci/CD integration, and gives feedback during code review with branch analysis and pull request decoration.
