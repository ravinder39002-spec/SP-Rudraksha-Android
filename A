# SP Rudraksha — Mobile Cloud Build

This project includes a GitHub Actions workflow at:
`.github/workflows/build-aab.yml`

## Mobile-friendly build route

1. Create/sign in to a GitHub account.
2. Create a new repository (for example `sp-rudraksha-android`).
3. Upload the contents of this ZIP to the repository, including the `.github` folder.
4. Open **Actions** → **Build SP Rudraksha AAB** → **Run workflow**.
5. When the workflow finishes, download the artifact named `sp-rudraksha-release-aab`.

Important:
- This workflow produces an **unsigned release AAB**. Google Play production publishing requires a properly signed app bundle.
- Do not put OTPs, UPI PINs, bank passwords, or other secrets in the repository.
- For final publishing, configure Android/Google Play signing securely through GitHub/Play Console secrets and Play App Signing.
- Before publishing, verify the final app's Privacy Policy URL, Data Safety declarations, payment QR assets, screenshots, and package-name registration.
