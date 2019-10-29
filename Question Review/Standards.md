## U.S. Organizations
- **The Office of Management and Budget (OMB)**:  
  The OMB assists the President in overseeing the preparation of the federal budget and to supervise its administration in Executive Branch agencies.
- **Defense Contract Audit Agency (DCAA)**:  
  DCAA provides audit and financial advisory services to Department of Defense (DoD) and other federal entities.
- **NSA/CSS**:  
  The National Security Agency/Central Security Service (NSA/CSS) is a crypto-logic intelligence agency of the United States government. It is administered as part of
the United States Department of Defense. NSA is responsible for the collection and analysis of foreign communications and foreign signals intelligence, which involves cryptanalysis. NSA is also responsible for protecting U.S. government communications and information systems from similar agencies elsewhere, which involves cryptography. 
The Central Security Service (CSS) is created to coordinate intelligence activities and cooperation between NSA and U.S. military cryptanalysis agencies.
- **NIST**:  
  The National Institute of Standards and Technology (NIST) is a measurement standards laboratory which is a non-regulatory agency of the United States Department of Commerce. The institute's official mission is to promote U.S. innovation and industrial competitiveness by advancing measurement science, standards, and technology in ways that enhance economic security and improve quality of life.

## Security Standards
High level security policies are supported by more detailed security standards.

![](https://lh3.googleusercontent.com/tA0V5EcZnp-EHLazgiLlTVI-eoopjWc8MTMgaWTyPjfJNgTaJxtfTQi10szA8r-hVgH52xK0bHN_KQ)

Security standards can be broadly categorized into two categories:
- Internal
- External

External standards can be further classified based on the issuer:
- Industry standards
- Government standard

External standards can also be classified based on the extent of recognition:  
- National: National security standards are often more focused and inclusive of local customs. eg. Federal Information Processing Standards (FIPS)
- International: International standards are usually more comprehensive and generic.

### NIST Standards
NIST programs assist in improving the quality and capabilities of software used by business, research institutions and consumers. They help secure electronic data and maintain availability of critical electronic services by identifying vulnerabilities and cost-effective security measures.

NIST have the statutory responsibility to set security standards and guidelines for sensitive Federal systems but these standards are selectively adopted and used by the private sector on a voluntary basis as well.

The computer security division Information Technology Laboratory (ITL) periodically publishes bulletins and the Special Publications 500 (SP 500) and 800 (SP 800) series. While the SP 500 series are more generic Information Technology related publications, the SP 800 series organize information technology security publications separately.

NIST also includes computer security-related Federal Information Processing Standards (FIPS).

-- **Gist**  
- National Institute of Standards and Technology (NIST)
  + Special Publications
	  - SP 500 : generic information technology related
	  - SP 800 : information technology security related
  + Federal Information Processing Standards (FIPS)

-- **Details about Special Publications (SP):**  
- **SP 800-12: An Introduction to Computer Security**  
  Categories of security controls
  - management controls
  - operational controls
  - technology controls.

- **SP 800-14: Generally Accepted Principles and Practices for Security IT Systems**  
  IT system's stakeholders: 
  - management
  - internal auditors
  - users
  - system developers
  - security practitioners

- **SP 800-18: Guide for developing Security Plans for Federal Systems**  
- **SP 800-27: Engineering Principles for Information Technology Security**  
- **SP 800-30: Risk Management Guide for IT**  
  Risk management process considers following major steps along with others:  
  - control categories
  - cost-benefit analysis
  - residual risk evaluation
  - mitigation options and steps  

  Risk mitigation strategy:  
![enter image description here](https://lh3.googleusercontent.com/dsQsItqjBmzPk57b-lcjVHlVqqdyWtsdY_kudNMra7mw5JAumVhaLvohBU5Fnccci9WBC-ZcTcLG4g)

- **SP 800-61: Computer Security Incident Handling Guide**  
- **SP 800-64: Security Considerations in the Information Systems Development Life Cycle**  
  Provides guidance for building security into the software development life cycle (SDLC) by:  
  - Identifying and mitigating security vulnerabilities and misconfigurations early in the SDLC.
  - Focusing on any engineering or design issues that may require redesign at a later stage of the SDLC.
  - Identifying shared security services that can be leveraged which reduces development cost and time.
  - Managing risk and facilitating executives to make informed risk related decisions.
- **SP 800-100: Information Security Handbook: A Guide for Managers**  
  As a CSSLP you should be familiar with the content of this guide.

- **Federal Information Processing (FIPS) standards**  
  FIPS publications are developed by NIST to address Federal requirements for:  
  - interoperability of disparate systems
  - portability of data and software and
  - computer security
  
  FIPS publications related to software security are:  
  - FIPS 140: Security Requirement for Cryptographic Modules
  - FIPS 186: Digital Signature Standard (DSS)
  - FIPS 197: Advanced Encryption Standard (AES)
  - FIPS 201: Personal Identity Verification (PIV) of Federal Employees and Contractors

### ISO Standards
- International Electrotechnical Commission (IEC): Develops electrotechnology standards
- International Telecommunications Union (ITU): Develops telecommunication standards

ISO in conjunction with IEC (prefixed as ISO/IEC) has developed several International Standards that are directly related to information security.
- **ISO/IEC 15408 – Evaluating Criteria for IT Security (Common Criteria)**
  Commonly known as the Common Criteria.
  
  Common Criteria elements:  
  - The product or system that is being evaluated is known as the **Target of Evaluation (TOE)**.  
  - The **Protection Profile (PP)** is used to create a set of generalized security requirements.  
  - The **Security Target (ST)** expresses the security requirements and specifies the security functions.  

  ISO/IEC 15408 Evaluation Assurance Level (FSMMSSF)  
![enter image description here](https://lh3.googleusercontent.com/Mlq-IiMOvxDfE2AyQDTikTXAjtLN1qe9GzO71wktfdxcwrvAmvPY3PHlhR85akINdcsNkIuf66HJ5Q)

- **ISO/IEC 21827:2008 – Systems Security Engineering Capability Maturity Model (SSE-CMM)**
  1. **Performed Informally**: Base processes are performed. 
  2. **Planned and Tracked**: Project-level definition, planning, and performance verification issues are addressed. 
  3. **Well-Defined**: The focus is on defining and refining a standard practice and coordinating it across the organization. 
  4. **Quantitatively Controlled**: This level focuses on establishing measurable quality goals and objectively managing their performance. 
  5. **Continuously Improving**: At this level, organizational capability and process effectiveness are improved.

- ISO/IEC 25000:2005 – Software Engineering Product Quality
- ISO/IEC 27000:2009 – Information Security Management System (ISMS) Overview and Vocabulary
- **ISO/IEC 27001:2005 – Information Security Management Systems Requirements**
- ISO/IEC 27002:2005/Cor1:2007 – Code of Practice for Information Security Management
- ISO/IEC 27005:2008 - Information Security Risk Management
- ISO/IEC 27006:2007 – Requirements for Bodies Providing Audit and Certification of Information Security Management Systems
- ISO 28000:2007 - Specification for security management systems for the supply chain

### PCI Standards
- **Payment Card Industry Data Security Standard (PCI DSS)**  
  PCI-DSS is for vendors who store, process or transmit cardholder data.  
  PCI-DSS Control Objectives:  
  - Build and Maintain a Secure Network
  - Protect Cardholder Data
  - Maintain a Vulnerability Management Program
  - Implement Strong Access Control Measures
  - Regularly Monitor and Test Networks
  - Maintain an Information Security Policy

- **Payment Application Data Security Standard (PA-DSS)**
PA-DSS is for vendors who do not store, process or transmit cardholder data.

- **Organization for the Advancement of Structured Information Standards (OASIS)**

## Best Practices
- **Open Web Application Security Project (OWASP)**
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTU4OTY5NjczOCw1NTk4ODc5NzUsLTYxOT
YwNTEwMyw4OTIyMzY5NzAsMTM1MzAzMjAzMiwtNzE1NzAzNzQ4
XX0=
-->