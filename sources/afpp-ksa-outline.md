# AFPP Exam KSA Outline
*Source: Nacha AFPP Item Development Guide, 2026 SME Version (slides 25–36)*

---

## 1000: Fundamentals of Faster Payments

### 1001: Knowledge of the types, applications, and impact of faster payments rails (e.g., individual and organizational benefits, economic benefits, financial inclusion)
- Describe the types, features, and applications of U.S. faster payments network rails (e.g., ACH, TCH RTP Network, FRB FedNow, debit card networks)
- Identify uses cases (e.g., payroll, disbursements, bill pay, claims) that are a good fit for faster payments types (e.g., P2P, B2C, C2B, B2B, G2C, C2G, B2G, A2A)
- Describe the impact and benefits of faster payments for stakeholders (e.g., speed of settlement, availability of funds, predictability, efficiency, security, enriched payment data, 24/7/365, additional functional capabilities such as request for payment and request for information)
- Distinguish between instant/immediate and same-day payments
- Describe end-user funds availability timing and corresponding interbank settlement methods for each faster payment rail
- Explain the relevance of irrevocability of final funds for each faster payment rail
- Identify the factors that impact the adoption and application of faster payments solutions (e.g., customer base, vendor relationships, existing technology, current and future products and services, ubiquity, interoperability, corporate culture/goals, reporting and financial institution reconciliation)
- Distinguish between payer authorization requirements by rail
- Explain the purpose and benefits of confirmation of payee
- Explain the usage of message types (i.e., value or non-value)
- Explain how faster payments impact end-user cash flow management
- Explain how faster payments impact financial institution liquidity management
- Describe the points of financial institution liquidity management in correspondent/respondent relationships

### 1002: Knowledge of the roles, responsibilities, and requirements of faster payments stakeholders (e.g., network operators, financial institutions, correspondents, bankers banks, corporate credit unions, third parties, value added services, merchants, consumers, regulators, core processors)
- Identify the roles and responsibilities of faster payments stakeholders
- Describe the eligibility requirements of faster payments stakeholders based on network (e.g., ACH, FedNow, RTP, Card Networks)
- Describe the relationships between faster payments stakeholders

### 1003: Knowledge of the attributes of faster payments solutions/mechanisms based on platform (e.g., push vs. pull, messaging, dollar limits, SLAs)
- Differentiate between faster payments rails that allow credit push only versus credit push and debit pull
- List the types of messaging capabilities for each faster payments rail
- Differentiate between the dollar limits for each faster payments rail
- Describe the network service level agreements applicable to faster payments

### 1004: Knowledge of the types and functions of participation
- Describe the different types of participation by rail
- Distinguish the message types required to be supported depending on the manner in which the financial institution participates in the network (e.g., receive only must certify for receiving PACS.008)

---

## 2000: Faster Payments Operations and Process Flows

### 2001: Financial institutions' procedures for payment processing via faster payments networks/platforms
- Identify the requirements by rail for financial institutions prior to receiving/originating transactions
- Identify the steps involved in faster payments transactions by network rail
- Describe the processes required for message validation (e.g., digital signature validation, schema validation)

### 2002: Settlement types, applications, and processes
- Identify faster payments rails settlement types/methods (e.g., Real-Time Gross, deferred)
- Describe how faster payments settlement types/methods impact payments stakeholders and systems
- Identify faster payments rails' requirements for end-user funds availability
- Describe the impact of faster payments settlement types on reconciliation of Fed/Joint accounts
- Differentiate between accounting cycles by rail

### 2003: Factors that impact message acceptance and rejection
- Explain how status responses from receiving financial institutions increase payment completion rates
- Identify the points of failure in the payment flow (e.g., at the sending financial institution, network operator, receiving financial institution)
- List the factors that cause a faster payment to fail
- Identify methods or techniques for mitigating message rejections and failures
- Identify the responsibilities of sending financial institutions when receiving message rejections and failures

### 2004: Exception handling processes for faster payment rails
- Identify the ways payments/messages lead to the build-out of exception processes
- Identify tools offered by faster payments rails to enable exception processing in a reasonable amount of time (e.g., messages, alerts, notifications)
- Identify methods faster payments rails use to aggregate exceptions data and identify patterns
- Identify methods faster payments rails use to reduce exception processing
- Explain when and why receiving financial institutions allow accept without posting responses
- Identify the allowable time frames for resolving accept without posting responses
- Compare the procedures for implementing requests for returns across faster payments rails
- Explain when and why financial institutions allow requests for returns and reversals
- Identify the allowable time frames for processing requests for returns
- Identify the methods faster payments rails use to create, record, and retain information needed for post-transaction exception evaluation (e.g., payment tracing, incident tracking)

### 2005: Types and purposes of back-office systems and functions for processing payments (e.g., OFAC screening, fraud control, AML compliance, deposit systems)
- Describe how faster payments rails impact OFAC screening processes
- Describe how faster payments rails impact AML compliance processes
- Describe how faster payments rails impact fraud detection processes
- Describe how faster payments rails impact deposit systems
- Describe the reporting requirements necessary to process faster payments
- Identify types of back-office systems' controls for processing faster payments
- Identify back-office systems needed to meet audit (or reconciliation) requirements

### 2006: Interoperability considerations regarding foreign and domestic payment systems
- Explain interoperability differences across faster payments rails
- Identify faster payments rails that allow cross-border payments
- Identify the data fields, format, and standards required for interoperability of foreign and domestic payments systems
- Identify barriers and solutions to cross-border interoperability of faster payments rails
- Identify risk factors related to cross-border payments (e.g., terrorism financing, currency fluctuations, infrastructure stability)

### 2007: Types of user transparency and notifications provided by faster payments networks/platforms stakeholders
- Identify the types and functions of status messages
- Identify the remittance information provided by faster payments rails
- Describe the remittance information disclosure requirements for faster payments rails

### 2008: Payment network process flows by participation level
- Differentiate payment process flows by rail
- Distinguish between clearing and settlement processes by rail

### 2009: Availability, permissible maintenance windows, and outage notifications by network
- Define the availability expectations for accessing faster payments rails
- Identify system maintenance and outage notification requirements
- Describe straight through processing expectations of faster payment rails and implications of transaction rejects (e.g., transaction timeouts)

### 2010: Procedures for reporting fraudulent and/or suspicious activity related to faster payments
- Identify which faster payments rails require reporting to stakeholders for fraud
- Identify methods and messages used for reporting fraud (e.g., Cam56 for RTP/FedNow, return codes)
- Identify the different fraud classifications with available messages
- Identify faster payments rails' requirements and options for reporting suspicious activity

---

## 3000: Faster Payments Risk Management

### 3001: Types of risks present in faster payments
- Describe the operational risks present in faster payments
- Describe the cross-channel risks present in faster payments
- Describe the compliance risks present in faster payments
- Describe the fraud risks present in faster payments
- Describe the liquidity risks present in faster payments
- Describe the technology risks present in faster payments
- Describe the credit risks present in faster payments

### 3002: Types and application of internal controls
- Identify commercially reasonable methods and techniques used to detect fraud (e.g., trend analysis, machine learning, predictive and behavioral modeling, anomalous transaction detection, enhanced due diligence, confirmation of payee)
- Describe the application of fraud detection and mitigation techniques for different types of fraud
- Identify types and applications of internal controls used to mitigate risk related to faster payments
- Identify barriers to the implementation of internal controls for faster payments
- Identify limitations of internal controls for mitigating types of faster payments risks
- Describe how service disruptions impact faster payments system integrity
- Identify risk assessment methodologies applicable to faster payments
- Explain the use of process flows in risk assessment for faster payments
- Identify the reasons for implementing prefunding requirements

### 3003: Customer onboarding programs, policies, and procedures
- Explain why customer onboarding programs are important for managing risk related to faster payments
- List the elements of a customer identification program (CIP)
- Describe the responsibilities of parties involved in a customer identification program (CIP)
- Identify additional requirements for faster payment customers that use Request for Payment functionality

### 3004: Types and applications of authentication channels and methods for transactions performed via faster payments solutions
- Identify the types of authentication methods used for faster payments transactions
- List the parties involved in faster payments transactions who need to be authenticated
- Compare the features and functions of authentication types by faster payments rail

---

## 4000: Technology Considerations for Enabling Faster Payments

### 4001: Types and purposes of technology components of faster payments networks/platforms
- List the critical technology components of faster payments rails
- Describe the purpose and function of an application programming interface (API) in the context of faster payments
- Explain the concept of directory as it relates to faster payments
- Identify methods for protecting data in transit and at rest (e.g., tokenization, encryption)
- Identify methods for connecting with faster payments platforms (e.g., direct, via third parties)
- Identify the purposes, functions, and benefits of directories used to support faster payments
- Compare the use of directories for faster payments with other industries (e.g., email and mobile phone networks)
- Explain the need for governance around directories that support faster payments
- Describe security considerations related to the use of directories (e.g., data, data mining, access)

### 4002: Purpose and application of messaging standards for faster payments platforms
- Define ISO 20022 and its application to faster payments
- Define ISO 8583 and its use for push to card
- Identify the messaging standards used with faster payments rails
- Identify the value and non-value messages within each faster payment rail

### 4003: ISO 20022 message categories and usage
- Explain the purpose of the two key components of ISO 20022 (i.e., message structure, data dictionary)
- Differentiate between value, non-value, system, and reporting message types
- Identify the messages financial institutions must accept to participate in instant payment rails

### 4004: Faster payments overlay and value-added services
- Identify types of value-added and overlay services for faster payments
- List examples and characteristics of value-added and overlay services
- Describe how value-added and overlay services support faster payments rails

---

## 5000: Governance Framework

### 5001: Rules and guidance applicable to faster payments networks/platforms
- Identify rule sets that govern faster payments rails
- Compare and contrast the Real-Time Payments and FedNow rules
- Identify which faster payments stakeholders have responsibility for PCI/DSS rule compliance
- Explain the relevance of FFIEC guidance to faster payments
- Explain the requirements set forth by each rule set applicable to faster payments

### 5002: Laws and regulations applicable to faster payments networks/platforms
- The interaction between private sector rules and other banking regulations
- Identify the payment rails governed by laws and regulations applicable to faster payments
- Identify the party responsible for governance of laws and regulations applicable to faster payments
- Differentiate between consumer and non-consumer regulations
- Compare and contrast private rule sets and federal regulation
- Describe the objectives of the data privacy laws
- Describe the obligations of faster payments stakeholders (by payment rail) under data privacy laws
- Explain the application of the Bank Secrecy Act and Anti-Money Laundering regulations to faster payments
- Explain the hierarchy of rules and regulations by payment rail

### 5003: Error resolution protections, rights, and liabilities of payers and payees
- Explain the liability of a payer for a misdirected payment
- Differentiate the applicability of error resolution protections under Regulation E and UCC4A
- Explain the liabilities and error resolution responsibilities of the sending and receiving financial institutions
- Define an error on a faster payment

### 5004: The role of client/customer agreements and disclosures with respect to faster payments products and services
- Identify the required agreements for each payment rail
- Identify the required disclosures for each payment rail
- Describe the roles of agreements among faster payments stakeholders
- Describe the roles of disclosures among faster payments stakeholders
- Compare warranties and indemnities by rail and rule set
