# Oracle Vercel Canary

A deliberately low-risk, non-production canary repository used to qualify the ChatGPT ↔ GitHub ↔ Vercel workflow before any real Oracle project is connected.

## Purpose

- Verify ChatGPT can read and write this GitHub repository.
- Verify Vercel can import and deploy the repository.
- Verify preview/production deployment visibility and logs.
- Verify Git changes trigger deterministic redeployment.
- Provide a safe canary surface with no dependency on Oracle runtime state.

## Safety boundary

This repository must remain free of:

- credentials, tokens, private keys, cookies or secrets;
- `.env` files or environment-specific secret values;
- banking, payment or customer data;
- private Oracle evidence or authority artifacts;
- local Oracle runtime dependencies;
- production domains or production mutation authority.

A successful deployment proves only the GitHub/Vercel integration path. It does **not** grant or imply Oracle production authority.
