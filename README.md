# MoizWordPress Secure Audit Reports

This repository hosts automated website technical audit reports including performance, accessibility, and security analysis.

## Security & Privacy Compliance

To ensure complete client confidentiality and prevent unauthorized access:
- All audit report PDFs are encrypted on the server using **AES-256-GCM** before being pushed to this repository.
- Folder names are anonymous SHA-256 hashes of the target domain names.
- Decryption occurs entirely in the client's browser (Zero-Knowledge) when clicking the secure URL generated in the email draft.
