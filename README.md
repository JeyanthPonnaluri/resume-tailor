# Resume Tailor

Tailors one-page resumes to a job description and drafts application-form answers for Harshitha and Jeyanth. Downloads are named `Role_Name_Company.pdf`.

## Using it

1. Open the site and enter the passphrase. Tick "Keep unlocked on this device" on your own laptop or phone only.
2. Press **Settings** and paste your Claude API key, which starts with `sk-ant-`. To get one, go to console.anthropic.com, open **API Keys**, then **Create key**. The account needs a little credit under **Billing**.
3. Paste a job description, choose who it's for, press **Tailor resume**, then **Download PDF**.

## Privacy

- **Profiles:** the profile data (contacts, projects, internships) is stored encrypted in `index.html` and decrypts only in your browser with the passphrase.
- **API key:** your key is saved only in your browser and sent only to `api.anthropic.com`. Never commit an API key to this repository.
- **Search engines:** the page asks search engines not to index it.

## Updating

This site is a snapshot of the profiles as of October 2026. To change the profile content or the passphrase, ask Claude to rebuild `index.html`, then upload the new file over the old one.
