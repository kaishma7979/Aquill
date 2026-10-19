# Aquill – Aquatiis Legalisis

Web software for a legal and compliance practice in India.

**Version 0.1:** menu, responsive dashboard and demo data only. No database yet.

## Files

- `index.html` – page frame (sidebar, top bar, content area)
- `style.css` – look and layout for phone and laptop
- `app.js` – menu list, demo data, page switching

## Adding a new module

Add one line to the `MENU` list in `app.js`. Later steps will give each module its own file.

## Security rules

- Never put client passwords, OTPs, portal logins or secret keys in any file here.
- The only key that will ever appear in code is the Supabase public (anon) key. It is safe only when Row Level Security is turned on, which we will do in the database step.
- All names and numbers in this version are demo data.

## Roadmap

1. Foundation and dashboard (this version)
2. Supabase database and team login
3. Client Master
4. ROC/MCA tracker
5. Other modules, one at a time
