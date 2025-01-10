# SAST

**1. Performing SAST Scan**

Perform a Static Application Security Test (SAST) scan on the code before merging to identify potential vulnerabilities and security issues.

* **Codebase**: The collection of code files that make up the application.
* **SAST Rules**: Use the threat model to create custom rules that cover more vulnerabilities according to the application's business logic and from the threat model.


**Consumes:**

* **Threat Model**: Provides a comprehensive understanding of potential threats to the application.
* **Codebase**: The collection of code files that make up the application.

**Produces:**

* **SAST Rules**: Custom rules created based on the threat model to cover more vulnerabilities according to the application's business logic.
* **SAST Reports**: Detailed reports generated by the SAST scan, including identified vulnerabilities and recommended fixes.
* **SAST Coverage Data**: Data on the percentage of code covered by the SAST scan, helping identify areas that may require additional testing.