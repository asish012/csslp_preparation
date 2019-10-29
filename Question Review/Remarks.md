### Different kinds of risks
- **Residual risk**:  
  (residual risk) = (inherent risk) x (control risk)  
  Residual risk is the risk that remains after the implementation of mitigating security controls.
- **Inherent risk**:  
  Risks before considering controls. Risks that are inherent in the nature of the business and economy.
- **Control risk**:
  The likelihood of a vulnerability wont be caught even if all possible safety measures (controls) would be applied.
- **Detection risk**:  
  Detection risks are the risks that an auditor will not be able to find during audit.  
  Detection risk includes two types of risks. Sampling risk, Non-sampling risk.
  + Sampling risk: When an auditor falsely accepts or erroneously rejects an audit sample.
  + Non-sampling risk: When an auditor fails to detect a condition because of non applying the appropriate procedure or using procedures inconsistent with the audit objectives (detection faults).
- **Secondary risk**:  
  The secondary risk is an outcome of dealing with the original risk.

*Higher inherent risk doesn't mean that there will be vulnerabilities. Because there might be controls in place already against them.*

*Auditor has no control over Inherent risk or Control risk, only client has control over them*
*Auditor only has control over detection risk*

### NIACAP
Four minimum participants (roles) are required to perform a NIACAP security assessment.
- IS program manager
- Designated Approving Authority (DAA)
- Certification agent (certifier)
- User representative

-- **IS program manager**: is the primary authorization advocate, who is responsible for the Information Systems (IS) throughout the life cycle of the system development.  
-- **Designated Approving Authority (DAA)**: is the official with the authority to formally assume responsibility for operating a system at an acceptable level of risk.  
-- **Certification agent (certifier)**: provides the technical expertise to conduct the certification throughout the system life cycle.  
-- **User representative**: focuses on system availability, access, integrity, functionality, performance, and confidentiality in a Certification and Accreditation (C&A) process.

### DIACAP
Key participants
- Information Assurance Manager (IAM)

### Risk calculation
- **Single Loss Expectancy (SLE)**  
SLE = Asset value * Exposure Factor
- **Annual Rate of Occurrence (ARO)**:  
ARO is an expression of the number of incidents from a particular threat that can be expected in a year. Looking at historical incident data within your industry is a good start for determining what the ARO should be.
- **Annual Loss Expectancy (ALE)**  
ALE = SLE * ARO

The identification and reduction of the Total Risk using controls so that the Residual Risk is within the acceptable range or threshold, wherein business operations are not disrupted, is the primary goal of risk management.

### Penetration techniques
- **Demon dialing**: automatically tests every phone line in an exchange and tries to locate modems that are attached to the network.
- **Sniffing**: a protocol analyzer is used to capture data packets that are later decoded to collect information such as passwords or infrastructure configurations.
- **Dumpster diving**:

### Roles & Responsibilities
- **Data owner**: is usually a member of management, in charge of a specific business unit, and is ultimately responsible for the protection and use of a specific subset of information. Data owner determines the sensitivity or classification levels of data.
- **Chief Risk Officer (CRO)**:  CRO's are accountable for enabling the business to balance risk and reward (opportunities). 
- **Chief Information Officer**:  CIO's are responsible for the information technology and computer systems that support enterprise goals. The CIO reports to the chief executive officer (CEO), chief operations officer (COO), or chief financial officer (CFO).
- **Designated Approving Authority**:  also known as the accreditor (স্বীকৃতি দানকারী).
- **Information system auditor**: Information system auditor inspects whether the security policies, standards, guidelines, and procedures are efficiently performed in accordance with the company's stated security objectives. He is responsible for reporting the senior management about the value of security controls by performing regular and independent audits.
- **Information system security professional**: An informational systems security professional designs, implements, manages, and reviews the security policies, standards, guidelines, and procedures of the organization. He is responsible to implement and maintain security by the senior-level management.
- **Senior management**: A senior management assigns overall responsibilities to other individuals.

### MAC levels
Mission Assurance Categories (MAC) and confidentiality levels prescribed by DoD 8500.2
- **MAC I**: It states that the systems have high integrity and high availability.
- **MAC II**: It states that the systems have high integrity and medium availability.
- **MAC III**: It states that the systems have basic integrity and availability.

### Software Assurance Acquisition process
Activities performed in the planning phase of the software assurance acquisition process:  
- Determine software product or service requirements. 
- Identify associated risks. 
- Develop software requirements. 
- Create acquisition strategy. 
- Develop evaluation criteria and evaluation plan. 
- Define development and use of SwA due diligence questionnaires.

### Qualitative risk analysis
- A fast and low-cost approach to  analyze the risk impact and its effect
- Uses the likelihood and impact of the identified risks
- Establishes a basis for a focused quantitative analysis
- Conducted at  any point in a project life cycle
- The goal is to determine  proportion of effect and theoretical response.

Inputs to Qualitative risk analysis:
- Organizational process assets 
- Project Scope Statement 
- Risk Management Plan 
- Risk Register

### Quantitative risk analysis
Quantitative risk analysis is in-depth and often requires a schedule and budget for the analysis.
- Objectively determines the impact
- Involves matrices and models to determine impact
- Historical loss data is used to determine impact

### Models
- **Take-Grant Protection Model**:  
  Uses a directed graph to specify the rights
- **Biba Integrity Model**:  
  
- **Bella-LaPadula Model**:  
  Deals only with the confidentiality of classified material. It does not address integrity or availability.

### Something like model
- **SSE-CMM**:  
  + Provide Ongoing Skills and Knowledge
  + Manage Project Risk
  + Improve Organization's System Engineering Process

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
  
  The product or system that is being evaluated is known as the Target of Evaluation (TOE).  
  The Protection Profile (PP) is used to create a set of generalized security requirements.  
  The Security Target (ST) expresses the security requirements and specifies the security functions.  
  The relationships between the Protection Profile (PP), the Security Target (ST) and the Target of Evaluation (TOE).
![enter image description here](https://lh3.googleusercontent.com/tiEpqeawtCfXL6-lSEwv-2loS_d0jCmyBz7eMtKvozoQn6_hpujSPx7A1dxepMuAO4XXUXlhp9uTgA)

  ISO/IEC 15408 Evaluation Assurance Level (FSMMSSF)
![enter image description here](https://lh3.googleusercontent.com/Mlq-IiMOvxDfE2AyQDTikTXAjtLN1qe9GzO71wktfdxcwrvAmvPY3PHlhR85akINdcsNkIuf66HJ5Q)

- **ISO/IEC 21827:2008 – Systems Security Engineering Capability Maturity Model (SSE-CMM)**
  1. **Performed Informally**: Base processes are performed. 
  2. **Planned and Tracked**: Project-level definition, planning, and performance verification issues are addressed. 
  3. **Well-Defined**: The focus is on defining and refining a standard practice and coordinating it across the organization. 
  4. **Quantitatively Controlled**: This level focuses on establishing measurable quality goals and objectively managing their performance. 
  5. **Continuously Improving**: At this level, organizational capability and process effectiveness are improved.

- **ISO/IEC 25000:2005 – Software Engineering Product Quality**


### PCI Standards





tax 60
insurance 30
electricity + heating 100
housegeld 400
interest 250
capital 500

<!--stackedit_data:
eyJoaXN0b3J5IjpbNDIxMTc0NTI2LC0xOTk0Njk1NzUxLDEwMj
Q2MTcyNjksLTIxNDI4NDgzMjAsMTQxNzg5NzU4LC0xMjA5NjYx
ODk1LC0xNTM3MzE5OTQsMTU2OTU3ODM3OSwtMTcyOTIzMzkxNi
wxODExNjk1NTcxLDE3NjMwMzEyNTUsMzc5NjcyMzE2LC0xMDgw
OTM4NjQ0LC0xNDMzNDY1MTk2LC0xNTMxMzYxMjc3LC0yMTY3Mj
ExOTcsLTE3NDcxNDkyNjYsODkyODA2ODcsMTUyMjAzMDkyMywy
MTAyNzg2Mjk1XX0=
-->