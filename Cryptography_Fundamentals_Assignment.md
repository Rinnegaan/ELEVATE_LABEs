# Assignment: Fundamentals of Cryptography and Real-World Applications

**Course:** Cyber Security / Digital Forensics  
**Topic:** Encryption, Hashing, Digital Signatures, and Real-World Usage

---

## 1. Symmetric vs Asymmetric Encryption

### Symmetric Encryption
Symmetric encryption uses a **single shared key** for both encryption and decryption.

**Key Characteristics:**
- Faster and computationally efficient
- Suitable for large data encryption
- Key distribution is a challenge

**Examples:** AES, DES (obsolete), Blowfish

---

### Asymmetric Encryption
Asymmetric encryption uses a **public-private key pair**.

**Key Characteristics:**
- Slower than symmetric encryption
- Solves key distribution problem
- Used for authentication and secure exchange

**Examples:** RSA, ECC

---

## 2. File Encryption Using AES

AES is a symmetric encryption standard with key sizes:
- AES-128
- AES-192
- AES-256

**Advantages:**
- High security
- Resistant to brute-force attacks
- Industry standard

---

## 3. RSA Key Generation

RSA is based on large prime factorization.

**Key Sizes:**
- 2048-bit
- 4096-bit

**Usage:**
- Secure key exchange
- Digital certificates

---

## 4. Digital Signatures

Digital signatures provide:
- Authentication
- Integrity
- Non-repudiation

**Process:**
1. Hash the message
2. Encrypt hash with private key
3. Verify with public key

---

## 5. Hashing and Integrity Verification

Common hash algorithms:
- MD5 (obsolete)
- SHA-1 (deprecated)
- SHA-256 (secure)

**Use Cases:**
- Password storage
- File integrity verification

---

## 6. Comparison of Encryption Algorithms

| Algorithm | Type | Key Size | Security | Usage |
|---------|------|----------|----------|-------|
| AES | Symmetric | 128–256 | Very High | Data encryption |
| RSA | Asymmetric | 2048–4096 | High | Key exchange |
| DES | Symmetric | 56 | Low | Obsolete |
| ECC | Asymmetric | Small | Very High | Modern systems |

---

## 7. Real-World Applications

### HTTPS
- Uses TLS
- Combines RSA/ECC + AES
- Secures web traffic

### VPN
- Encrypts entire network traffic
- Uses AES, IPsec, OpenVPN

---

## 8. Findings and Conclusion

Cryptography ensures confidentiality, integrity, and authentication.
AES is ideal for bulk data, RSA for secure exchange, and hashing for integrity.

**Conclusion:**  
Cryptography is the backbone of modern cybersecurity systems.

---

**End of Assignment**
