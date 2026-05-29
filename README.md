# 🔐 ScottsTechX OpenSSL

<p align="center">
  <img src="https://img.shields.io/badge/OpenSSL-SSL-TLS-00ff88?style=for-the-badge&logo=linux&logoColor=black" alt="OpenSSL"/>
  <img src="https://img.shields.io/badge/Open-Source-00ff88?style=for-the-badge&logo=github&logoColor=black" alt="Open Source"/>
</p>

> **SSL/TLS toolkit — generate certificates, test connections, encrypt data, analyze handshake.**

---

## ⚡ What It Does

OpenSSL provides SSL/TLS functionality — generate keys, create certificates, test servers, encrypt/decrypt data, and analyze cryptographic operations.

## 🚀 Quick Usage

```bash
# Generate private key
openssl genrsa -out key.pem 2048

# Create self-signed cert
openssl req -new -x509 -key key.pem -out cert.pem -days 365

# Test SSL connection
openssl s_client -connect target.com:443

# Check certificate
openssl x509 -in cert.pem -text -noout

# Encrypt file
openssl enc -aes256 -in plain.txt -out encrypted.bin

# Decrypt file
openssl enc -d -aes256 -in encrypted.bin -out plain.txt
```

---

MIT © 2026
