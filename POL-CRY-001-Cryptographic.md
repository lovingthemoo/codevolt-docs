# CodeVolt Cryptographic Policy

**Document ID:** POL-CRY-001  
**Version:** 1.0  
**Effective Date:** February 3, 2026  
**Review Date:** February 3, 2027  
**Owner:** Rook (rook@codevolt.co.uk)  
**Approved By:** Senior Management

---

## 1. Purpose

This policy establishes governance for cryptographic controls to protect the confidentiality, integrity, and authenticity of information.

---

## 2. Scope

This policy applies to:
- Use of encryption for data protection
- Cryptographic key management
- Digital signatures and certificates
- Approved cryptographic algorithms and protocols

---

## 3. Governance

### Policy Owner
The Information Security Manager owns this policy and ensures:
- Alignment with organizational risk appetite
- Compliance with regulatory requirements
- Review of cryptographic standards

---

## 4. Encryption Requirements

### Data at Rest
Sensitive and confidential data shall be encrypted using:
- Industry-standard algorithms (e.g., AES-256)
- Appropriate key lengths
- Secure modes of operation

### Data in Transit
Data transmitted over networks shall be protected using:
- Modern transport security protocols
- Strong cipher suites
- Certificate-based authentication where appropriate

### Prohibited Algorithms
The following are not permitted for security-sensitive purposes:
- MD5 for integrity verification
- SHA-1 for digital signatures
- DES or 3DES for encryption
- SSL v2 or v3

---

## 5. Key Management

### Key Generation
Cryptographic keys shall be generated using:
- Cryptographically secure random number generators
- Approved key generation procedures
- Secure key generation environments

### Key Storage
Keys shall be protected by:
- Storage separate from encrypted data
- Access restricted to authorized personnel
- Appropriate physical and logical controls

### Key Lifecycle
Key management includes:
- Secure distribution mechanisms
- Defined rotation schedules or triggers
- Secure destruction when no longer needed

---

## 6. Certificates

Digital certificates used for authentication or encryption shall:
- Be issued by trusted certificate authorities
- Be valid and not expired
- Be renewed before expiration
- Be revoked if compromised

---

## 7. Review

This policy is reviewed:
- At least annually
- When cryptographic standards evolve
- Following security incidents involving cryptography

---

**Review Cycle:** Annual  
**Next Review:** February 3, 2027  
**Policy Owner:** Information Security Manager

---

*© 2026 CodeVolt. ISO 27001:2022 Compliant.*
