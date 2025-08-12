# OBELISK
Obfuscated Binary Encryption with Layered Integrity &amp; Secure Keying.

## Project Overview:
OBELISK is a cutting-edge encryption application focusing on future-proof security and covert protection mechanisms. It offers:
* Multi-layered encryption using two distinct, independently-keyed algorithms applied in succession. This architecture aims to safeguard against a potential cryptanalytic breakthrough in one algorithm (e.g., AES), ensuring that compromise of one layer does not expose plaintext.
* Steganographic obfuscation as the final pipeline step: data is seamlessly hidden within benign files (e.g., images/audio), making the very existence of encrypted data non-obvious and dramatically increasing resistance to forensic analysis.
* Robust integrity and advanced key management rounding out the security model.

![Logo](Imgs/main_flow.svg)

