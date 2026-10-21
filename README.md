# TRUST WALLET LEARNING

An independent, mobile-friendly educational website about crypto basics and wallet safety.

## Publish using GitHub Pages on Android
1. Sign in at https://github.com/
2. Create a **public** repository named `trust-wallet-learning`.
3. Upload `index.html`, `styles.css`, and `script.js` to the repository's root folder.
4. Open repository **Settings** > **Pages**.
5. Under Build and deployment, choose **Deploy from a branch**.
6. Select branch `main` and folder `/(root)`, then tap **Save**.
7. Wait a few minutes and refresh the Pages settings screen. GitHub will show the published address.

## Important security notes
- This site is independent and is not affiliated with the official Trust Wallet service.
- It does not ask visitors for recovery phrases, private keys, or passwords.
- GitHub Pages hosts static files. It does not create user accounts or provide a secure login backend.
- If you later need sign-in, use a trusted authentication provider such as Firebase Authentication or Supabase Auth, configured carefully. Never store plaintext passwords or put admin/service-role secrets in browser code.
