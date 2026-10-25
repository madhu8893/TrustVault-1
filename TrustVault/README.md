# TrustVault — Secure Document Management Demo

This is a single-page front-end prototype inspired by the supplied TrustVault design.

## Run locally
Open `index.html` in a browser, or run a local server from this folder:
```bash
python -m http.server 8000
```
Then visit http://localhost:8000.

## Important security limitation
This is a UI prototype only, not a production-secure document-sharing service. It stores account data and document metadata in browser localStorage, does not store uploaded file bytes, and does not enforce security on a server. Do not use real passwords or confidential documents. A secure submission needs a backend, hashed passwords, server-side authorization, protected file storage, and server-generated audit events.
