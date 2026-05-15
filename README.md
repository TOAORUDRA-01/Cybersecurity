# Cybersecurity Notes Site

Static HTML site for the cybersecurity notes collection.

## Local preview

You can open `index.html` directly in a browser, or run a simple local server.

### PowerShell

```powershell
cd d:\Cybersecurity
python -m http.server 8080
```

Then visit http://localhost:8080

## Deploy

Deploy the folder as a static site (e.g., Vercel, Netlify, GitHub Pages). The clean routes are handled by folder `index.html` redirects.

### Vercel

- Framework preset: `Other`
- Build command: (leave empty)
- Output directory: `.`

## Routes

- /cryptography
- /90-day-plan
- /linux-bash
- /networking-fundamentals
- /web-security-owasp
