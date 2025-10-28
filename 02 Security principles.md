# Security principles
## Learning principles
- understand the CTA Triand and its importance.
- Explain Risk, Privacy and Accountablity.
- Relate security principles to real-world cyber incidents.
# CIA Triad
- The CIA Triad forms the foundation of information security.
- Each element ensures that information remains safe and trustworthy.

| Element              | Description                                                 | Example                                               |
| -------------------- | ----------------------------------------------------------- | ----------------------------------------------------- |
| **Confidentiality**  | Ensures data is accesible only to authorised users          | Encrypting file using passwords, access control lists |
| **Integrity**        | Ensures data is accurate, consistent and not tempered with. | Using hashing, digital signatures, checksums          |
| **Availablity**      | Ensures system and data are available whwn needed           | Redudant servers, backups, DDos protection            |

<img width="237" height="212" alt="download" src="https://github.com/user-attachments/assets/10ed4d78-0654-43d6-b68d-487a241fd014" />

# Risk, privacy, and accountablity
## Risk
-Defenition: probublity of a threat exploiting a vulneralblity to cause harm.
##Components:
- Threat = something that can cause damage
- Vulnerbility = wekness that can be exploited
- impact = damage if threat is realized
#Formula
Risk = Threat * Vulnerablity * Impact

 # Example:
 - Threat: phishing
 - Vulnerability: Employee lack of awareness
 - Impact: credential theft, financial loss

# Privacy
- protecting personal and sensitive information of individuals.
- Goverened by laws like GDPR, DPDP act(India), HIPAA.

# Key particles:
- data minimization
- informed consent
- data anonymization
Example: a healthcare app must not share user health data without consent
#Accountablity
Ensuring every action in an IT system can be traced back to an individual

# Achieved through:
- logging & auditing
- user access tracking
-  non-repudation mechanisms
  Example: audit logs in firewalls to trace malicious user actions

# Real-world case studies
| case                        | description                                    | violated principle
| --------------------------- | ---------------------------------------------- | -------------------------
| wannacry(2017)              | ransomeware disabled hospital system worldwide | availablility
| equifax breach (2017)       | personal data of 143M user leaked              | confidentiality and integrity
| twitter hack(2020)          | insider access to admin tools                  |confidentiality and accountablity
