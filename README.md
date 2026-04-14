 SIM Legacy Shield (SLS) 🛡️🇳🇬

 🚧 Project Status
SLS is currently in early stage development (architecture & validation phase).

This repository contains the core concept, system design, and planned implementation.

Contributions, feedback, and collaborations are welcome.



 ⚡ What is SLS?
SIM Legacy Shield (SLS) is a USSD based identity verification tool designed to help Nigerians detect risks associated with recycled SIM cards before linking them to their BVN.

It acts as a safety check between SIM activation and BVN linkage, helping users avoid permanent identity conflicts under the one-time linkage policy.


 🎯 Why This Matters
From May 2026, BVN phone number changes are restricted. This creates a serious risk when recycled SIM cards still carry traces of a previous owner’s financial identity.

SLS helps prevent:
 Identity collision
 Accidental linkage to another person’s financial history
 Permanent BVN linkage errors



 🧠 How It Works (Simple Flow)
Dial → Check → Score → Decide

1. User buys and activates a SIM  
2. Before linking BVN, user dials a USSD code (e.g. *7006#)  
3. SLS runs a verification check  
4. Risk score is generated:  
   - 🟢 Safe  
   - 🟡 Caution  
   - 🔴 High Risk  
5. User decides to proceed or discard the SIM  



 👵 Real-Life Scenario
A woman buys a recycled SIM.

After activation, she starts receiving bank alerts meant for someone else.

Before linking her BVN, she dials *7006#.

SLS flags the SIM as 🔴 High Risk.

She avoids linking her identity to a compromised number.



 🏗️ System Architecture

User → USSD Gateway → API Server → Risk Engine → Signal Ledger  
                                      ↓  
                               Agent Dashboard  

 Core Components
 USSD Gateway: Entry point for all users (no internet required)  
 API Server: Handles requests and routes data  
 Risk Engine: Calculates risk scores using defined rules  
 Signal Ledger: Stores anonymized patterns  
 Agent Dashboard: Used by verified agents for validation  



 🔐 Privacy & Data Protection
SLS is built with a strict privacy-first approach.

  What we DO NOT store:
- Phone numbers  
- BVN  
- NIN  
- Names or personal identity data  

  What we store:
- Anonymized signal patterns  
- Non-identifiable activity fingerprints  
- Risk-related metadata  

All stored data is hashed using SHA-256.

---

 ⚖️ Identity Safeguard (Evidence Support)
If a SIM is flagged as 🔴 High Risk, SLS generates a Verification Reference Code.

This code can be presented at a bank as supporting evidence of a recycled SIM issue.

It helps:
- Support legitimate user complaints  
- Reduce wrongful BVN linkage restrictions  
- Improve transparency during dispute resolution  



 🛡️ Anti-Abuse & Trust System
To prevent false reporting and misuse:

- Standard user report: +1 weight  
- Verified agent report: +5 weight  
- High-risk threshold: 6+  

Only strong, consistent signals trigger a 🔴 High Risk status.



 🌍 Accessibility (Grandma-Proof Design)
The system is designed for everyday users, including non-technical individuals.

Key protections:
- Double confirmation for critical actions  
- "Press 0 to cancel" on every screen  
- Session auto-revert on timeout  
- Support for local languages (Pidgin, Yoruba, Hausa, Igbo)  



 🔄 Current Approach (Independent Operation)
SLS is designed to function independently of restricted or private infrastructure.

It operates as a user-driven verification layer using:
- Community reporting  
- Agent validation  
- Internal risk scoring logic  



 🛠️ Getting Started

 Planned Stack
- Backend: Node.js or Python  
- USSD Integration: Africa’s Talking / Termii  
- Database: PostgreSQL / Redis  

 Status
Early-stage development (architecture and validation phase)

 Open Roles
- Backend Developers  
- USSD Engineers  
- Security Researchers  
- Product Designers  



 🚀 Vision
SIM Legacy Shield is built as a public-interest solution to protect Nigerians during identity transitions.

Future direction:
- Partnerships with telecom operators  
- Integration with financial institutions  
- Expansion into broader identity risk auditing  



 📜 License
MIT License ‎    
