 SIM Legacy Shield (SLS) 🛡️🇳🇬
 
‎🚀 Current Sprint (April 2026)

 [In Progress] API Research: Investigating NIBSS/TIRMS endpoints for SIM-to-BVN verification (@Odusina).
‎[New] Architecture: Finalized the 6step "Grandma-Proof" USSD flow and Risk Scoring heuristics.
‎[Goal] Integration of SHA-256 hashing for Zero-PII data storage.

‎
‎    The Identity Status Verification Framework for Nigeria's Single Linkage BVN Policy 
‎
‎       Executive Summary
‎
‎Starting May 1, 2026, the CBN has restricted BVN phone changes to once in a lifetime. SLS is a proactive risk mitigation framework designed to verify the status of recycled Sim cards for financial ghosts before they are permanently bonded to a user's digital identity.
‎
‎  The Solution: 6 Step Grandma Friendly Workflow.
‎
‎We prioritize accessibility using USSD to ensure the tool works without data or smartphones.
‎
‎1.  SIM Acquisition: User buys and registers a new SIM.
‎2.  Activation: SIM is verified via NIN and becomes active.
‎3.  ⚠️ The SLS Identity Verification: Before linking the BVN, the user dials a USSD code (e.g, *7006#).
‎4. Verification Engine: SLS queries the Zero-PII Ledger for historical flags and prompts the user for  Self-Declared Signals (e.g, Do you receive bank alerts for a stranger?).
‎5. Risk Scoring: Our Heuristic Engine applies weights (+1 for User reports, +5 for Agent flags) to generate a Confidence Rated Status: 🟢 Safe, 🟡 Caution, or 🔴 High Risk.
‎6. Decision: User chooses to link their BVN or discard the compromised SIM.
‎
‎  Technical Collaboration (Open Roles)
‎
‎     🏗️ System Architecture (The 5 Pillars)
‎USSD Gateway: Entry point for Grandma-Proof accessibility.
‎API Server: The Brain routing signals between the user and the ledger.
‎Risk Engine: Logic center that calculates scores and confidence levels.
‎Signal Ledger (Hashed): A SHA-256 anonymized database of identity ghosts.
‎Agent Dashboard: A verification portal for 3MTT Agents to validate high risk flags.

‎ ⚖️ Regulatory Alignment & Compliance
‎
‎TIRMS vs SLS: A Complementary Ecosystem
‎In March 2026, the NCC launched the  Telecoms Identity Risk Management System (TIRMS) to protect the Nigerian telecommunications space from identity theft and fraudulent SIM recycling .
‎ 🏛️ TIRMS protects the system: It provides a backend synchronization layer for Mobile Network Operators (MNOs) and Financial Institutions.
‎ 🛡️ SLS protects the user: It provides a consumer facing USSD interface, allowing the everyday Nigerian to perform a Pre Linkage Identity Verification before committing their BVN to a recycled MSISDN.
‎
‎    Data Privacy & Legal Guardrails (NDPR/NDPA)

‎SIM Legacy Shield is built with a Privacy by Design philosophy to ensure full compliance with Nigerian laws:
‎   Zero-PII Ledger Policy: SLS does not store names, BVNs, or phone numbers. We store SHA-256 Anonymized Hashes. This allows us to recognize a "Ghost SIM" across different users without ever knowing the actual identity of the person holding it. 
‎   Consent Based Identity Verification : No SIM Identity Verification is triggered without explicit user authorization via the USSD interface.
‎   Transparency: Risk scores (🟢/🟡/🔴) are generated based on metadata and header patterns, not by "hacking" private databases.

⚖️ Regulatory Support & The Identity Safeguard
‎The Identity Safeguard acts as a  Decision Support & Evidence Generator. If a SIM is flagged 🔴 High Risk, SLS generates a unique Verification Reference Code. This allows the user to present documented findings of a "Recycled SIM Conflict" to their financial institution. This transparency helps bank officials verify the legitimacy of an appeal for a BVN linkage correction, ensuring the "Once in a Lifetime" policy remains effective while protecting innocent consumers from recycled identity errors.

User Safety & Logic (Grandma-Proofing)

‎To ensure SIM Legacy Shield (SLS) remains accessible and safe for non tech savvy Nigerians, the following Safety are required in the USSD/API logic:
‎
‎    User Safety & Logic (Grandma-Proofing)
‎To ensure SIM Legacy Shield (SLS) remains accessible and safe for non tech savvy Nigerians, the following Safety are required in the USSD/API logic:

‎Double Confirmation for Critical Actions: Any action that alters a SIM to BVN link must require a two digit confirmation (e.g, "Press 55 to confirm") to prevent accidental pocket dialing or mindless clicking.

‎    Universal Exit (The '0' Rule): Every single USSD screen must include a "Press 0 to Cancel" option to ensure the user never feels trapped in a process.

‎    Session Persistence & Auto Revert: If a session times out or a phone loses signal mid process, the system must auto revert to the last Safe State to prevent partial or hanging identity updates.

‎   Language Accessibility:The logic should support Pidgin and local language prompts like Yoruba, Igbo, Hausa to ensure the May 2026 BVN deadline information is clear to all demographics.


Current Phase: Decentralized Validation (Plan B Strategy)

‎  To ensure SLS remains functional regardless of official API timelines, we are implementing a Community Assisted Validation model to provide real time risk intelligence.
‎

‎   Community Intelligence Network: Enabling users and local agents to report "identity ghosts" on recycled SIMs.

‎   Risk Scoring Heuristics: Building internal logic to flag high risk linkages based on SIM age and CBN Once in a Lifetime policy triggers.

‎   Fintech Trust Signals: Leveraging anonymized verification patterns from private sector partners to confirm identity health.

‎ 🛡️ Anti-Abuse & Trust Layer

‎ To prevent malicious flagging, we use Signal Weighting:
‎Standard User Report: +1 Weight.
‎Verified 3MTT Agent Report: +5 Weight (Gold Standard).
‎System Threshold: A score of 6+ is required to generate 🔴 a high Risk identity safeguard status.
‎

    Project Vision & Sustainability
    
‎SIM Legacy Shield (SLS) is a social impact solution designed to bridge the digital divide created by the May 2026 BVN deadline.
‎
‎    B2B Licensing: We aim to provide Telcos and Financial Institutions with "Safety Rail" logic to reduce customer churn and identity errors during national policy shifts.

‎    Public Sector Utility: Positioning as a third party framework to assist the NCC/NIMC in protecting vulnerable demographics during the 2026 transition.
‎  
     Scalability: The logic is designed to be modular and adaptable for future national identity audits or SIM linkage updates beyond 2026.
