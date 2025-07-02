#  Controls Assessment – Medisync Health Systems

This file contains the results of the internal controls audit conducted for Medisync Health Systems.

| Control                              | Status | Notes                                                                 |
|--------------------------------------|--------|-----------------------------------------------------------------------|
| Least Privilege                      | ❌ No  | Admin accounts are reused across departments                         |
| Separation of Duties                 | ❌ No  | Developers have access to production patient data                    |
| Multi-Factor Authentication (MFA)   | ✅ Yes | Enforced on AWS and internal tools                                   |
| Encryption                           | ✅ Yes | Data is encrypted at rest and in transit                             |
| Intrusion Detection / Prevention     | ❌ No  | No IDS/IPS system deployed                                           |
| Firewall                             | ✅ Yes | AWS firewalls with defined rule sets                                 |
| Backups                              | ✅ Yes | Daily encrypted backups performed using offline external drives      |
| Disaster Recovery Plan               | ❌ No  | No documented recovery or restoration procedures                     |
| Antivirus / Endpoint Security        | ✅ Yes | Installed and updated across all employee systems                    |
| Password Policy                      | ❌ No  | Weak password reuse is common; no enforcement                        |
| Password Management System           | ❌ No  | No vault or credential manager implemented                          |
| Logging and Monitoring               | ❌ No  | No centralized log collection or real-time monitoring                |
| Physical Security (Access Controls) | ✅ Yes | Biometric locks and secured server room                              |
| Remote Access VPN                    | ✅ Yes | All remote workers use company-managed VPN                           |
| Legacy Systems                       | ✅ Yes | No legacy systems in use; all tech updated within last 2 years       |

> Risk Score: **High (8/10)** due to lack of separation of duties, password management, and real-time detection systems.
