# Wingua Privacy Policy (GitHub Pages)

**GitHub repository:** [https://github.com/Lesymm/Wingua-privacy-policy](https://github.com/Lesymm/Wingua-privacy-policy)

**Live site (Pages):** [https://lesymm.github.io/Wingua-privacy-policy/](https://lesymm.github.io/Wingua-privacy-policy/)

## What gets published

The policy users and App Store Connect should read is **`index.html`** at the root of this repository.

This **`README.md`** is only for contributors (it is not the legal policy text).

## If GitHub Pages shows this README instead of the policy

GitHub Pages sometimes uses Jekyll and serves `README.md` when the site does not pick up `index.html` as the homepage.

1. Commit an empty **`.nojekyll`** file at the repo root (this folder includes it — keep it in git).
2. In the GitHub repo: **Settings → Pages** — source **Deploy from a branch**, branch **`main`**, folder **`/ (root)`**.
3. Ensure **`index.html`** is committed on `main` and pushed.

After a refresh, the site should show the styled **Wingua — Privacy Policy** page from `index.html`.

## Clone and update

```bash
git clone https://github.com/Lesymm/Wingua-privacy-policy.git
cd Wingua-privacy-policy
# edit index.html
git add index.html .nojekyll README.md
git commit -m "Privacy: …"
git push
```

Optional: sync wording from `docs/legal/wingua-privacy-policy.md` in the main Wingua app monorepo after counsel review.

## Optional EAS override

If the live URL differs, set `EXPO_PUBLIC_PRIVACY_POLICY_URL` in Expo / EAS environment variables.
