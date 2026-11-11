# 0xali3n.github.io

Personal knowledge website for **Chinmay Chandragoud Patil** (Chinmay Patil).

Public URL (after you publish): https://0xali3n.github.io/

This site complements the primary portfolio at https://chinmay.life/. It is a static, multi-page GitHub Pages project.

## Local preview

From this folder:

```bash
python3 -m http.server 8080
```

Then open http://localhost:8080/

Or:

```bash
npx --yes serve -l 8080
```

## Regenerate HTML

Page content is generated from `scripts/build.mjs`:

```bash
node scripts/build.mjs
```

## Deploy (manual, only when you approve)

See the project report from the Cursor session, or:

1. Initialize git in this folder (if needed)
2. Add remote `https://github.com/0xali3n/0xali3n.github.io.git`
3. Commit locally
4. `git push -u origin main`

Do not push until content is reviewed.

## Stack

- Static HTML
- Shared CSS (`assets/css/site.css`)
- Minimal JS for mobile nav (`assets/js/site.js`)
- No framework runtime required on GitHub Pages
