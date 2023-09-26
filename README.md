# DISCLAIMER
This content has been published in support of the claims made in the book [The Language of Deception: Weaponizing Next Generation AI](https://www.amazon.com/Language-Deception-Weaponizing-Next-Generation/dp/1394222548/), written by [Justin Hutchens](https://www.linkedin.com/in/justinhutchens/) and published by [Wiley](https://www.wiley.com/). **This content is intended exclusively for academic purposes.**

# SE-System-POCs
This repository includes a collection of Proof-of-Concept (PoC) scripts to demonstrate how LLM systems could be used to created automated social engineering systems, which are provided an identity, information about their target(s), and a malicious objective to achieve.

# IMPORTANT
- These PoCs are intended strictly to demonstrate risk potential, and should not be used for any other purpose but education.
- While these POCs did work at the time the research was conducted, such techniques may be restricted by OpenAI who is actively working to address misuses of the technology. Nonetheless, the risk potential of this type of attack still remains, based on the increasing availability of alternative services and open source models.

# Proof of Concepts
The three PoCs provided include the following:
1. HelpDesk_CredHarvest_POC.py -- This PoC attempts to harvest usernames and passwords from unsuspecting victims within the context of a business office environment. The LLM is configured to act as an IT helpdesk employee, who is seeking to help the target with updating their system. The LLM is configured to acquire the password of the target user.
2. SSN_Fraud_POC.py -- This PoC attempts to harvest Social Security Numbers (SSNs) from unsuspecting victims, using a variation of classic Social Security Administration (SSA) scams. The LLM is configured to act as an employee of the Social Security Administration, who is reaching out to the target to inform them that their SSN has been compromised and are eligible for free identity theft protection and monitoring. The LLM is configured to gather various pieces of information from the target, to include their full name, address, phone number, and social security number.
3. WireFraud_POC.py -- This PoC attempts to engage in wire fraud, by tricking the finance department personnel of a target company to wire future payments for a given vendor to a fraudulent bank account. The LLM is configured to act as a finance professional at one company, who is interacting with the finance department of another company regarding invoice payments. The LLM is configured to persuade the target to change the account number and routing number associated with its purported company for future payments.

# Demonstration
[![LLM SE POCs](https://img.youtube.com/vi/MHprHneOO3c/0.jpg)](https://www.youtube.com/watch?v=MHprHneOO3c "LLM SE POCs")
