## 🧩 Decrypting Secrets: “Stacked Secrets” CTF Challenge

**Category**: CRYPTO | **Difficulty**: Easy  
**Author**: Ateeb Ali

---

### 🔐 Challenge Overview

You're given an RSA-encrypted message and keys. No hints — just a whisper:
> _"Sometimes, the public and private are too close for comfort."_  

---

### 🛠️ Solution Steps

1. Load the private key and ciphertext into [CyberChef](https://gchq.github.io/CyberChef/) or [AnyCrypt](https://anycrypt.com/).
2. Decrypt the message using RSA decryption with provided values.
3. The output appears in hex:
  41 43 4d 7b 52 53 41 5f 44 33 43 30 64 33 44 5f 53 75 63 63 33 24 24 46 75 31 31 59 7d
4. Use the “From Hex” operation to get the flag.

---

### 🎯 Final Flag

ACM{RSA_D3C0d3D_Succ3$$Fu11Y}

---

### 🧠 Key Concepts Covered

- RSA encryption/decryption
- Online decryption tools
- Hex to ASCII conversion

