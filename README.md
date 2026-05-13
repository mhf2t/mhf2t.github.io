# Your Portfolio Site

This is your personal portfolio website. You manage everything through a clean web form at `/admin` — you don't need to edit any of these files directly.

## What's in this folder

```
portfolio/
├── index.html              ← Your public website (what visitors see)
├── admin/
│   ├── index.html          ← The admin panel loader
│   └── config.yml          ← Defines the upload form fields
├── _data/
│   ├── projects.json       ← All your projects (auto-updated by admin)
│   └── about.json          ← Your about page (auto-updated by admin)
└── uploads/                ← Images & files you upload (auto-managed)
```

## How to add a new work

1. Go to `https://yoursite.netlify.app/admin`
2. Log in with your email (one-time setup, then it remembers you)
3. Click **Projects → All Projects**
4. Click **Add Item** under the "Projects" list
5. Fill in: Title, Category, Year, Description, Image, Tags, Link
6. Click **Publish** — your new work appears on the live site in ~60 seconds

## Categories available

- Research
- BIM
- Simulation
- Tools & Demos
- Architecture
- Student Work
- Art

(To add more categories, edit the dropdown options in `admin/config.yml`.)

## Updating your About / Contact info

In the admin panel, click **About Page → About Content** and edit any field. Your bio, role, email, social links are all there.

## Your live URLs

- Public site: `https://yoursite.netlify.app`
- Admin panel: `https://yoursite.netlify.app/admin`

(Once deployed, "yoursite" will be replaced with your actual Netlify subdomain.)
