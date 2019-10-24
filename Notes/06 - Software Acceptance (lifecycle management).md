## Table of Content

- Pre-Release and Pre-Deployment
	- Completion Criteria
		- Documentation
		- DRP
		- BCP
- Risk Acceptance
	- Exception Policy
	- Sign-off
- Post-Release
	- Validation and Verification
		- FIPS
		- Common Criteria
	- Independent Testing
		- Third Party
---

### Key concepts:
-   Know the difference between certification and accreditation (C&A) and understand how V&V can be used for C&A.
- Impact of the software to the existing system/process.
---

### Guidelines for Software Acceptance

**Acceptance Criteria**  
- Functionality
- Performance
- Quality
- Safety
- Privacy and Security

**SD3**  
Defense in Depth implies Security in Design, Default, and Deployment.

**EULA** End User Licensing Agreements
**DMCA** Digital Millennium Copyright Act
**Acceptance**: The final checkpoint to discover missed and unforeseen security vulnerabilities and to validate the presence of security controls.

### Software Acceptance Considerations
**What needs to considered when building software in-house**:  
![](https://lh3.googleusercontent.com/aty-udi1Qnisxl0mj8jQsrCYli0prEc6PPl_Jq6-MAF8cdIBu8P6oJpK8LQhwPlsEEVEMMU61f5bxA)

 -- **Completion Criteria**  
- Generate the requirements traceability matrix (RTM) that includes security requirements besides functional requirements. 
  (deliverable: **RTM**)
- Generate the threat model. 
  (deliverable: **Threat Model**)
- Review and sign-off on the security architecture. 
  (deliverable: **Security architecture design**)
- Review of code for security vulnerabilities. 
  (deliverable: **Code review report**)
- Completion of security testing after application testing. 
  (deliverable: **Security test report**)
- Completion of documentation before the deployment. 
  (deliverable: **Documentation**)

-- **Change Management**  
Is a subset of configuration management.
Change in any part of a software can potentially introduce new security vulnerabilities, thereby increase risk. Therefore, Newer versions of software need to be approved, tracked and validated to ensure that the current state and level of security has not been reduced.

All changes need to be formally requested by the software development organization which is usually done through the Program Management Office (PMO). It must then be evaluated for approval or rejection by members of the Configuration/Change Board (CCB).

-- **Approval to Deploy or Release**  
Without approvals, no change should be allowed to the production environment. And before any new installation of software, a risk analysis needs to be conducted and the residual risk determined.
The authorizing official (AO) is responsible for change approvals.

-- **Risk Acceptance and Exception Policy**

-- **Documentation**  

**What needs to considered when buying software: See Supply Chain Security chapter**  

<!--stackedit_data:
eyJoaXN0b3J5IjpbMTA5MDIwNzE0OCwtMTMwMjc0NTY0MiwtMT
kzNzQ0MzIyNCwtMTg5NjM5NDMxNiwtMTE5NDgyMDkzMCw1NjY5
NDAwMTIsMTI2MDE1ODUxMiwxMzg5MzU5MTMzLDY3OTM2MDI5Ny
wxNDc2MzA1Nzc3LC03NDcwNTM2MzQsLTczMjQ3MjYxOCwtMTc2
MjE2MDE5OSwyMDczNDI5MzQzLDY3NTgxMjk1LDE0MDg5NDgyMT
hdfQ==
-->