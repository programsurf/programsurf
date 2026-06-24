# Sunwoo Lee

Ph.D. Researcher @ [KENTECH](https://www.kentech.ac.kr/) · Post-Quantum Cryptography · AI agent Security


## Research Interests

- Formal Verification of Cryptographic Implementation
- PQC Optimization
- Responsible Disclosure
- AI agent Security


## Security Contributions

**CVE Discoveries**

*Cryptographic Libraries*

- [![cve](https://cve-badge.li/CVE-2026-42764)](https://www.cve.org/CVERecord?id=CVE-2026-42764) — OpenSSL NULL pointer dereference in QUIC server initial packet handling (invalid/expired token), reachable when address validation is disabled via `SSL_LISTENER_FLAG_NO_VALIDATE` (Moderate, CWE-476)
- [![cve](https://cve-badge.li/CVE-2026-5264)](https://www.cve.org/CVERecord?id=CVE-2026-5264) — wolfSSL DTLS 1.3 ACK heap buffer overflow (High, CWE-122)
- [![cve](https://cve-badge.li/CVE-2026-5295)](https://www.cve.org/CVERecord?id=CVE-2026-5295) — wolfSSL PKCS7 ORI OID stack buffer overflow (High, CWE-121)
- [![cve](https://cve-badge.li/CVE-2026-5393)](https://www.cve.org/CVERecord?id=CVE-2026-5393) — wolfSSL dual-algorithm CertificateVerify out-of-bounds read (Medium, CWE-125, Experimental; test credit)
- [![cve](https://cve-badge.li/CVE-2026-5448)](https://www.cve.org/CVERecord?id=CVE-2026-5448) — wolfSSL X.509 date buffer overflow in notAfter/notBefore compatibility API (Low, CWE-120)
- [![cve](https://cve-badge.li/CVE-2026-5504)](https://www.cve.org/CVERecord?id=CVE-2026-5504) — wolfSSL PKCS7 CBC padding oracle via unvalidated interior padding bytes (Medium, CWE-354)
- [![cve](https://cve-badge.li/CVE-2026-5507)](https://www.cve.org/CVERecord?id=CVE-2026-5507) — wolfSSL session cache arbitrary free via unvalidated deserialized pointer (Medium, CWE-761)
- [![cve](https://cve-badge.li/CVE-2026-34610)](https://github.com/smuellerDD/leancrypto/security/advisories/GHSA-636g-jxv4-v4gr) — leancrypto X.509 CN length truncation enables certificate identity impersonation (CVSS 5.9, CWE-681)
- [![cve](https://cve-badge.li/CVE-2026-5598)](https://www.cve.org/CVERecord?id=CVE-2026-5598) — Bouncy Castle BC-JAVA FrodoKEM non-constant time comparison enabling private key leakage (High, CWE-385)

*AI / ML Frameworks*

- [![cve](https://cve-badge.li/CVE-2026-34981)](https://github.com/pavelzbornik/whisperX-FastAPI/security/advisories/GHSA-6rc7-r867-c635) — whisperX-FastAPI SSRF via unvalidated URL fetch with extension bypass (CVSS 5.8, CWE-918)
- [![cve](https://cve-badge.li/CVE-2026-35483)](https://github.com/oobabooga/text-generation-webui/security/advisories/GHSA-85fx-vw25-4c95) — text-generation-webui path traversal in `load_template()` leaks .jinja/.yaml files (CVSS 5.3, CWE-22)
- [![cve](https://cve-badge.li/CVE-2026-35484)](https://github.com/oobabooga/text-generation-webui/security/advisories/GHSA-w3cv-4447-5hf5) — text-generation-webui path traversal in `load_preset()` leaks arbitrary .yaml files (CVSS 5.3, CWE-22)
- [![cve](https://cve-badge.li/CVE-2026-35485)](https://github.com/oobabooga/text-generation-webui/security/advisories/GHSA-hqg5-487v-5mc6) — text-generation-webui path traversal in `load_grammar()` leaks arbitrary files (CVSS 7.5, CWE-22)
- [![cve](https://cve-badge.li/CVE-2026-35486)](https://github.com/oobabooga/text-generation-webui/security/advisories/GHSA-jvrj-w5hq-6cp2) — text-generation-webui SSRF in superbooga RAG extensions enables cloud credential theft (CVSS 7.5, CWE-918)
- [![cve](https://cve-badge.li/CVE-2026-35487)](https://github.com/oobabooga/text-generation-webui/security/advisories/GHSA-mfgg-vvc6-vqq7) — text-generation-webui path traversal in `load_prompt()` leaks arbitrary .txt files (CVSS 5.3, CWE-22)
- [![cve](https://cve-badge.li/CVE-2026-56823)](https://github.com/Significant-Gravitas/AutoGPT/security/advisories/GHSA-rq9m-xvc7-v9h6) — AutoGPT Platform IDOR in webhook ping endpoint allows cross-user webhook enumeration, OAuth provider type leakage, and unauthorized ping triggering due to missing ownership verification (CVSS 4.6, CWE-284/CWE-639)

*Web Applications & Tooling*

- [![cve](https://cve-badge.li/CVE-2026-48819)](https://www.cve.org/CVERecord?id=CVE-2026-48819) — @hey-api/openapi-ts prototype chain substitution in `buildClientParams` template via crafted `$query___proto__` slot key (Moderate, CWE-1321)
- [![cve](https://cve-badge.li/CVE-2026-46556)](https://github.com/flaskbb/flaskbb/security/advisories/GHSA-xq32-9g7q-7297) — FlaskBB SSRF in `get_image_info()` via unrestricted avatar URL enabling cloud metadata access and internal port scanning (CVSS 6.5, CWE-918)


**Bug Reports**

- [![GitHub Issue](https://img.shields.io/badge/SymCrypt-Issue%20%2355-181717?logo=github)](https://github.com/microsoft/SymCrypt/issues/55)
  [![GitHub Issue](https://img.shields.io/badge/pq--crystals%2Fdilithium-Issue%20%23110-181717?logo=github)](https://github.com/pq-crystals/dilithium/issues/110)
  — Microsoft SymCrypt ML-DSA `UINT16` signing counter wrap causes nonce reuse

- ![wolfSSL](https://img.shields.io/badge/wolfSSL-Reported-orange)
  — LMS `wc_LmsKey_Sign` insufficient buffer size and missing callback validation

- ![wolfSSL](https://img.shields.io/badge/wolfSSL-Reported-orange)
  — Negative ASN.1 integer overflow in CRL number field decoding

- ![wolfSSL](https://img.shields.io/badge/wolfSSL-Reported-orange)
  — RSA exponent stack buffer overflow in `wolfSSL_EVP_PKEY_print_public`

- ![wolfSSL](https://img.shields.io/badge/wolfSSL-Reported-orange)
  — DTLS fragment reassembly reads uninitialized heap contents

- ![wolfSSL](https://img.shields.io/badge/wolfSSL-Reported-orange)
  — DTLS 1.3 `word16` truncation on handshake send size

- ![wolfSSL](https://img.shields.io/badge/wolfSSL-Reported-orange)
  — Missing `hashLen` sanity check in `wc_dilithium_verify_ctx_hash`

- [![GitHub Issue](https://img.shields.io/badge/Z3-Issue%20%239463-181717?logo=github)](https://github.com/Z3Prover/z3/issues/9463)
  — `sat.smt=true` returns invalid models for BV comparator predicates; `smt.elim_unconstrained` abstracts comparators to fresh booleans and witness reconstruction satisfies each independently without joint consistency

- [![GitHub Issue](https://img.shields.io/badge/liboqs-Issue%20%232392-181717?logo=github)](https://github.com/open-quantum-safe/liboqs/issues/2392)
  [![GitHub Issue](https://img.shields.io/badge/MAYO--C-Issue%20%2310-181717?logo=github)](https://github.com/PQCMayo/MAYO-C/issues/10)
  — MAYO `mayo_sign_signature` returns `MAYO_OK` after 256-attempt rejection sampling exhaustion, assembling signature from invalid solution buffer

**Patch Contributions**

- [![GitHub PR](https://img.shields.io/badge/OpenSSL-PR%20%2330611-181717?logo=github)](https://github.com/openssl/openssl/pull/30611)
  — Uninitialized QUIC connection IDs (CWE-457)

- [![GitHub PR](https://img.shields.io/badge/OpenSSL-PR%20%2330612-181717?logo=github)](https://github.com/openssl/openssl/pull/30612)
  — Channel memory leak on initial secret failure (CWE-401), backported to 3.3–4.0

**Standards Contributions**

- ![NIST](https://img.shields.io/badge/NIST-FIPS%20204-blue)
  ![ML-DSA](https://img.shields.io/badge/ML--DSA-%CE%BA%20counter-lightgrey)
  — Reported κ counter width ambiguity in FIPS 204 to NIST `pqc-comments` on 2026-03-31


## Selected Publications

- "When Removing Reductions Goes Wrong: Auditing Reduction Placement in Production ML-DSA Implementations", Cryptology ePrint Archive 2026/1032 [[ePrint](https://eprint.iacr.org/2026/1032)]
- "When API Keys Leak: Securing AI Services with Post-Quantum Proof-of-Possession", ICAIIC 2026 [[IEEE Xplore](https://ieeexplore.ieee.org/document/11454376)]
- "A Maturity Model for Crypto-Agility in Substation Automation Systems", ICAIIC 2026 [[IEEE Xplore](https://ieeexplore.ieee.org/document/11454308)]
- "Signed-Only Execution for Third-Party Pre-Trained Models in AI Platforms", IEEE BigData 2025 [[IEEE Xplore](https://ieeexplore.ieee.org/document/11401569)]
- "Evaluating Post-Quantum Cryptography for Resource-Constrained AMI Gateways", IEEE CNS 2025 [[IEEE Xplore](https://ieeexplore.ieee.org/document/11194968)]

## Honors
- **NATO CCDCOE Locked Shields** — Technical Division (2022, 2023)  

## Contact

[![Homepage](https://img.shields.io/badge/Homepage-sunwoo--lee-FF5722)](https://sites.google.com/view/sunwoo-lee)
[![Email](https://img.shields.io/badge/Email-sunwoolee%40kentech.ac.kr-blue)](mailto:sunwoolee@kentech.ac.kr)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-sunwoolee-0A66C2?logo=linkedin)](https://www.linkedin.com/in/sunwoo-lee-b2485b341?utm_source=share_via&utm_content=profile&utm_medium=member_android)
