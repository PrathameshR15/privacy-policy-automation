# Privacy Policy - Social Media Automation Workflow

Privacy Policy webpage for **Masterstroke Technosoft Private Limited** covering our testing-stage AI-powered social media automation workflow using **Activepieces** and **Meta Graph APIs** (Facebook Pages & Instagram Accounts).

## Project Structure

```
├── privacy-policy.html   # Main responsive privacy policy page
├── index.html            # Static root fallback redirect to /privacy-policy
├── vercel.json           # Vercel configuration for clean URL routing (/privacy-policy)
└── README.md             # Documentation & deployment guide
```

## How It Works

- Accessible at `/privacy-policy` (configured in `vercel.json`).
- Mobile-responsive, clean typography (Inter font), zero-dependency vanilla HTML/CSS.
- Includes all Meta compliance sections:
  - Account info & OAuth access token security
  - Granular Meta permission mappings (`pages_manage_posts`, `instagram_content_publish`, etc.)
  - Handling of uploaded images and AI-generated captions
  - Third-party processing disclosure (Meta, Activepieces, AI providers)
  - Testing-stage disclaimer banner
  - Data retention, user rights, and deletion request procedure
  - Company details for Masterstroke Technosoft Private Limited (Pune, India; support@mstblockchain.com)

## Deploying to Vercel

### Option 1: Via Vercel CLI
```bash
npx vercel
```

### Option 2: Via GitHub / Git Repository
1. Push this directory to GitHub or GitLab.
2. Import the repository in [vercel.com](https://vercel.com).
3. Framework Preset: **Other** / Root Directory: `./`.
4. Click **Deploy**. The page will be instantly available at `https://<your-project>.vercel.app/privacy-policy`.
