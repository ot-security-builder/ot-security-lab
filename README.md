# ot-security-lab
Getting started with Operational Technology Security Engineering
# CISA - ICS Cybersecurity Practices (100W) 
## Hak 5 Rubber Ducky - It is like an USB drive that can be used to steal confidential information from computer
- Latest iteration detects operating system and modify it's payload accordingly to steal information - It is terrifying OMG
- Ducky code is written in ducky script programming language
- Payload is built using the script and the Payload Studio to compile ready to execute malicious program
### Phishing Attack
- Steal personal information
- Adversary masking themselves in a familiar avatar

### Spearphising Attack
- Malicious attack targeting particular company
- Message rushes you
- Spelling mistakes
- Weird language
- Strange Web Addresses
- Likely contains an attachment to the email
- Charity Requests

### How to prevent becoming a victim of Phising?
- Read through the message for spelling mistakes
- DO NOT open attachments
- Slow down
- Reach out to the company or the sender directly via phone or email using company's official email address

#### Note: Countermeasures seems to be an approach followed by industrial systems to deal with security breach

## CISA 100W – ICS Cybersecurity Practices (completed Oct 13, 2026) Notes

### 1. Operational Security (OPSEC)
- OPSEC = protecting information that attackers could piece together to target ICS environments.
- CISA's **Shields Up** campaign: recommendations, products, and resources to raise vigilance and inform the public about threats to critical infrastructure.

### 2. Common information collection techniques
- **Phishing:** mass deceptive emails.
- **Spear phishing:** targeted at a specific person or role.
- **Whaling:** targeted at executives and senior leaders.
- **Social engineering:** via geolocation (e.g., tagged photos revealing site locations) and social interactions.
- **Disguised malware:** hidden in common, benign-looking objects (e.g., USB drives, cables, gifts).

### 3. Equipment sanitization
- Sanitize equipment before repurposing or destroying it, so configs, credentials, and process data don't leak.

### 4. Defense-in-Depth
- Layered protection so no single failure exposes the system.
- **Physical security:** controlling access to sites, cabinets, and devices.
- **Data security:** protecting information at rest and in transit.

### 5. Air gaps
- An **air gap** means the OT network has no physical or network connection to IT or the internet.
- It's often treated as the main defense, but it's weaker than it sounds: USB drives, vendor laptops, and maintenance connections regularly cross it.
- Lesson: an air gap reduces risk but doesn't remove it. Removable media and vendor access still need controls.

### 6. Stuxnet (discovered 2010)
- Malware that targeted Iran's Natanz uranium enrichment facility.
- Widely believed to have entered the air-gapped network via infected USB drives.
- Targeted Siemens Step7 software and Siemens S7 PLCs controlling centrifuges.
- Changed centrifuge speeds to damage them, while showing operators normal readings on their HMIs.
- Why it matters: first well-known malware to cause **physical damage** through ICS, and proof that air gaps and "looks normal on screen" aren't enough.

### Terms to revisit
- OPSEC, Shields Up, whaling, Defense-in-Depth, Air gaps, Stuxnet
