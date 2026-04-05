# Sunwoo Lee

Ph.D. Researcher @ [KENTECH](https://www.kentech.ac.kr/) · Post-Quantum Cryptography · AI agent Security

## Research Interests

- Formal Verification of Cryptographic Implementation
- PQC Optimization
- Responsible Disclosure
- AI agent Security

## Security Contributions

**CVE Discoveries**
- [CVE-2026-34610](https://github.com/smuellerDD/leancrypto/security/advisories/GHSA-636g-jxv4-v4gr) — leancrypto X.509 integer truncation enabling CN identity impersonation (CVSS 5.9, CWE-681)
- [CVE-2026-34981](https://github.com/pavelzbornik/whisperX-FastAPI/security/advisories/GHSA-6rc7-r867-c635) — whisperX-FastAPI SSRF via unvalidated URL fetch with extension bypass (CVSS 5.8, CWE-918)
- [CVE-2026-35483](https://github.com/oobabooga/text-generation-webui/security/advisories/GHSA-85fx-vw25-4c95) — text-generation-webui path traversal in `load_template()` leaks .jinja/.yaml files (CVSS 5.3, CWE-22)
- [CVE-2026-35484](https://github.com/oobabooga/text-generation-webui/security/advisories/GHSA-w3cv-4447-5hf5) — text-generation-webui path traversal in `load_preset()` leaks arbitrary .yaml files (CVSS 5.3, CWE-22)
- [CVE-2026-35485](https://github.com/oobabooga/text-generation-webui/security/advisories/GHSA-hqg5-487v-5mc6) — text-generation-webui path traversal in `load_grammar()` leaks arbitrary files (CVSS 7.5, CWE-22)
- [CVE-2026-35486](https://github.com/oobabooga/text-generation-webui/security/advisories/GHSA-jvrj-w5hq-6cp2) — text-generation-webui SSRF in superbooga RAG extensions enables cloud credential theft (CVSS 7.5, CWE-918)
- [CVE-2026-35487](https://github.com/oobabooga/text-generation-webui/security/advisories/GHSA-mfgg-vvc6-vqq7) — text-generation-webui path traversal in `load_prompt()` leaks arbitrary .txt files (CVSS 5.3, CWE-22)

**Bug Reports**
- [Microsoft SymCrypt #55](https://github.com/microsoft/SymCrypt/issues/55) — ML-DSA UINT16 signing counter wrap causes nonce reuse (also reported upstream to [pq-crystals/dilithium #110](https://github.com/pq-crystals/dilithium/issues/110))

**Patch Contributions**
- [OpenSSL #30611](https://github.com/openssl/openssl/pull/30611) — Uninitialized QUIC connection IDs (CWE-457)
- [OpenSSL #30612](https://github.com/openssl/openssl/pull/30612) — Channel memory leak on initial secret failure (CWE-401), backported to 3.3–4.0

**Standards Contributions**
- Reported κ counter width ambiguity in FIPS 204 (ML-DSA) to NIST pqc-comments (2026-03-31) — spec-compliant implementations independently reproduce nonce reuse due to unspecified integer width

## Selected Publications

- "A Maturity Model for Crypto-Agility in Substation Automation Systems", ICAIIC 2026
- "Signed-Only Execution for Third-Party Pre-Trained Models in AI Platforms", IEEE BigData 2025
- "Evaluating Post-Quantum Cryptography for Resource-Constrained AMI Gateways", IEEE CNS 2025

## Honors
- **NATO CCDCOE Locked Shields** — Technical Division (2022, 2023)  

## Contact

[![Homepage](https://img.shields.io/badge/Homepage-sunwoo--lee-FF5722)](https://sites.google.com/view/sunwoo-lee)
[![Email](https://img.shields.io/badge/Email-sunwoolee%40kentech.ac.kr-blue)](mailto:sunwoolee@kentech.ac.kr)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-sunwoolee-0A66C2?logo=linkedin)](https://www.linkedin.com/in/sunwoo-lee-b2485b341?utm_source=share_via&utm_content=profile&utm_medium=member_android)
