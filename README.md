 SIM Legacy Shield (SLS) 🛡️🇳🇬

 
‎
‎    The Identity Auditor for Nigeria's One Shot BVN Era

‎
‎       Executive Summary
‎
‎Starting May 1, 2026, the CBN has restricted BVN phone changes to once in a lifetime. SLS is a proactive risk mitigation framework designed to audit recycled SIM cards for financial ghosts before they are permanently bonded to a user's digital identity.
‎
‎  The Solution: 6 Step Grandma Friendly Workflow.
‎
‎We prioritize accessibility using USSD to ensure the tool works without data or smartphones.
‎
‎1.  SIM Acquisition: User buys and registers a new SIM.
‎2.  Activation: SIM is verified via NIN and becomes active.
‎3.  ⚠️ The SLS Audit: Before linking the BVN, the user dials a USSD code (e.g, *7006#).
‎4. Verification Engine: SLS scans for incoming debt SMS patterns and fintech app registration conflicts.
‎5.  Risk Scoring: User receives a status:
🟢 Safe
🟡 Caution 
🔴 Risk.
‎6. Decision: User chooses to link their BVN or discard the compromised SIM.
‎
‎  Technical Collaboration (Open Roles)
‎
‎     IT Administration (Lead: @OdusinaDamilare): Mapping the USSD gateway and telecom API integrations.
‎   Security Research: Identifying common Financial Ghost patterns in recycled numbers.

‎ ⚖️ Regulatory Alignment & Compliance
‎
‎TIRMS vs SLS: A Complementary Ecosystem
‎In March 2026, the NCC launched the  Telecoms Identity Risk Management System (TIRMS) to protect the Nigerian telecommunications space from identity theft and fraudulent SIM recycling .
‎ 🏛️ TIRMS protects the system: It provides a backend synchronization layer for Mobile Network Operators (MNOs) and Financial Institutions.
‎ 🛡️ SLS protects the user: It provides a consumer facing USSD interface, allowing the everyday Nigerian to perform a Pre Linkage Audit before committing their BVN to a recycled MSISDN.
‎
‎    Data Privacy & Legal Guardrails (NDPR/NDPA)
‎SIM Legacy Shield is built with a Privacy by Design philosophy to ensure full compliance with Nigerian laws:
‎   Zero Storage Policy: SLS does not store sensitive PII (Personally Identifiable Information) such as full BVN or NIN digits.
‎   Consent Based Auditing: No SIM audit is triggered without explicit user authorization via the USSD interface.
‎   Transparency: Risk scores (🟢/🟡/🔴) are generated based on metadata and header patterns, not by "hacking" private databases.
‎   Rule of Law: The Emergency Brake feature acts as a Policy Recommendation, providing users with verifiable evidence to use in official bank appeal processes.


User Safety & Logic (Grandma-Proofing)

‎To ensure SIM Legacy Shield (SLS) remains accessible and safe for non tech savvy Nigerians, the following Safety are required in the USSD/API logic:
‎
‎    User Safety & Logic (Grandma-Proofing)
‎To ensure SIM Legacy Shield (SLS) remains accessible and safe for non tech savvy Nigerians, the following Safety are required in the USSD/API logic:
‎Double Confirmation for Critical Actions: Any action that alters a SIM to BVN link must require a two digit confirmation (e.g, "Press 55 to confirm") to prevent accidental pocket dialing or mindless clicking.
‎    Universal Exit (The '0' Rule): Every single USSD screen must include a "Press 0 to Cancel" option to ensure the user never feels trapped in a process.
‎    Session Persistence & Auto Revert: If a session times out or a phone loses signal mid process, the system must auto revert to the last Safe State to prevent partial or hanging identity updates.
‎   Language Accessibility:The logic should support Pidgin and local language prompts like Yoruba, Igbo, Hausa to ensure the May 2026 BVN deadline information is clear to all demographics.
