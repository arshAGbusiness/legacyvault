# LegacyVault

A digital estate and inheritance vault for Indian families: one place to map assets, store documents, manage nominees, and walk heirs from death certificate to claim.

**Live demo:** `https://<your-username>.github.io/<repo-name>/` (after enabling GitHub Pages)

## Features
- **Overview:** net estate, legacy health score (0-100) and one-tap fixes for gaps
- **Asset register:** banks, FDs, demat, mutual funds, PF, insurance, lockers, property, gold, plus loans and cards as liabilities
- **Nominee manager:** up to four nominees per item, simultaneous or successive, shares validated to 100%
- **Document locker:** expiry reminders, asset linking, will status
- **Settlement workflow:** trusted-contact report, multi-party attestation, owner-cancellable time-lock, per-institution claim packs, heir-restricted views, audit trail, printable
- **Backup:** JSON export and import

## Run locally
Open `index.html` in a browser. No build step, no dependencies.

## Deploy on GitHub Pages
1. Create a repository and upload `index.html` and `README.md` to the root.
2. Go to **Settings > Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then **Save**.
4. After a minute your site is live at the URL shown on that page.

## Important limitations
This is a front-end prototype. All data is stored in the visitor's browser (`localStorage`) and is **not encrypted, synced or uploaded**. Document uploads record only the file name. There is no login. Account Aggregator, DigiLocker, e-sign and real death verification are not implemented.

Before real use you need a backend with authentication, encrypted storage, audit logging and legal review (DPDP Act, Banking Laws (Amendment) Act 2025). Claim-pack checklists are typical examples and must be confirmed per institution. LegacyVault is a planning aid, not legal advice.
