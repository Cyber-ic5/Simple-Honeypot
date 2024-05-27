# Simple Honeypot

## Objective

The goal of the honeypot project was to exhibit a simple tripwire that can be adopted on Windows OS. This project was created to reinforce understanding of security concepts, defense strategies, and intrusion detection.

### Skills Learned

- Installment of basic honeypots.
- Event log analysis.
- Configuration of local security policy.

### Tools Used

- Oracle VM
  
## Steps

Ref 1: Created folder to base honeypot on.

![Screenshot (1700)](https://github.com/Cyber-ic5/Simple-Honeypot/assets/169179159/652911f7-859d-4301-895c-790d9f28f864)

Ref 2: Local security policy set to audit access to object for both Success and Failure.

![Screenshot (1701)](https://github.com/Cyber-ic5/Simple-Honeypot/assets/169179159/02a98860-9322-4ecf-8b75-2fff66179b05)

Ref 3 & 4: Security settings (advanced) for the created folder set to add a principle to be notified when object is accessed.

![Screenshot (1702)](https://github.com/Cyber-ic5/Simple-Honeypot/assets/169179159/e9976ad4-baa1-4281-b020-f5e1ed52d8d1)
![Screenshot (1703)](https://github.com/Cyber-ic5/Simple-Honeypot/assets/169179159/f094d0ce-92d4-4eaf-9cf0-e12318ace870)

Ref 5: "Administrator" account chosen as the principle.

![Screenshot (1704)](https://github.com/Cyber-ic5/Simple-Honeypot/assets/169179159/436aebca-e37e-45ad-bd6e-2ccff8dd911c)

Ref 6: Admin account confirmed to be in the auditing entries.

![Screenshot (1706)](https://github.com/Cyber-ic5/Simple-Honeypot/assets/169179159/16ae19dc-2735-4de7-8b43-cf864eac299c)

Ref 7: Splunk log snippet displaying event when folder is accessed.

![Screenshot (1721)](https://github.com/Cyber-ic5/Simple-Honeypot/assets/169179159/c15bcaa4-23ab-4913-92f6-7caddda108e7)
