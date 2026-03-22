# 📊 Risk Register – Web2 to Web3 Migration

## 🏢 Scenario

SecureCart Pvt. Ltd. migrating from Web2 to Web3 infrastructure.

---

## 🔐 Risk Table

Title: Risk Register – Web2 to Web3 Migration (SecureCart Pvt. Ltd.)

| ID | Asset              | Risk                             | Likelihood | Impact | Risk Level | Control                 | Owner           |
| -- | ------------------ | -------------------------------- | ---------- | ------ | ---------- | ----------------------- | --------------- |
| R1 | Smart Contract     | Vulnerability (Reentrancy, bugs) | High       | High   | Critical   | A.14 Secure Development | Dev Team        |
| R2 | Wallet             | Private Key Theft                | High       | High   | Critical   | A.9 Access Control      | Security Team   |
| R3 | API Gateway        | API Exploitation                 | Medium     | High   | High       | A.14 + WAF              | DevOps          |
| R4 | User Data          | Data Leakage                     | Medium     | High   | High       | A.10 Cryptography       | IT Team         |
| R5 | Blockchain Network | 51% Attack                       | Low        | High   | Medium     | Network Monitoring      | Blockchain Team |
| R6 | Admin Panel        | Unauthorized Access              | Medium     | High   | High       | RBAC (A.9)              | Admin           |
| R7 | Payment System     | Transaction Manipulation         | Low        | High   | Medium     | Smart Contract Audit    | Dev Team        |

Conclusion:
Critical risks identified in smart contracts and wallet security requiring immediate mitigation.


---

## 📌 Summary

Critical risks identified in smart contracts and wallet security.
