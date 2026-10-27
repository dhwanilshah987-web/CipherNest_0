# CipherNest - Zero-Trust Blockchain Vault

CipherNest is a modern, dark-themed zero-trust cloud vault and immutable ledger dashboard built with React, Vite, TypeScript, and Tailwind CSS.

## Features
- **Client-Side Encryption Pipeline**: Mock AES-256-GCM & ChaCha20-Poly1305 payload protection.
- **SHA-256 Digest Calculation**: Real-time browser-based WebCrypto hashing.
- **Block Explorer Ledger**: Inspect block headers, Merkle root state proofs, and validator node telemetry.
- **Proof of Integrity Auditor**: Verify file authenticity against block root signatures.
- **Binary Hex Inspector**: View formatted hexadecimal memory dumps of vault objects.

## Getting Started

### 1. Install Dependencies
```bash
npm install
```

### 2. Run Development Server
```bash
npm run dev
```

### 3. Build for Production
```bash
npm run build
```

## Deployment
Import directly into Vercel or Netlify. Pre-configured with SPA client-side routing (`vercel.json`).
