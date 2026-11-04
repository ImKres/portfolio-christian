# Christian Libuna — portfolio web app

Open `index.html` in a browser. Everything (styles, data and code) is in that one file; the only other file it needs is `assets/christian-libuna.jpg`.

## What's in it
- **Overview**: intro, highlights, featured projects, recent roles
- **Projects**: 8 case studies with filters; click one for problem, approach, result and stack
- **Experience**: 6 roles across Philtech, Fujitsu and LEAP, plus education
- **Skills**: click a skill to see which projects and roles used it
- **Certifications**: 10 Microsoft and AWS certifications with issue and expiry dates (from LinkedIn), plus training
- **Contact**: email (with a copy button) and LinkedIn
- Ctrl+K search, light/dark theme, phone layout with a bottom tab bar

Certification badges are the official Microsoft Learn and AWS images, saved in `assets/badges`. If a file is missing, the page loads it from Microsoft or AWS instead.

## Editing
All content lives in the `PROJECTS`, `JOBS`, `SKILL_GROUPS`, `CERTS` and `TRAINING` lists near the top of the `<script>` in index.html.

`style.css`, `script.js` and `theme-init.js` are left over from the earlier resume version and are no longer used. You can delete them.
