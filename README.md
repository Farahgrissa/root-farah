# root@farah — terminal portfolio

Farah Grissa's portfolio, styled as a Linux terminal (neon pink, violet and cyan palette).

## Run locally
Just open `index.html` in your browser (double-click), or:

```bash
python -m http.server 8000   # then http://localhost:8000
```

## Edit the content
Everything lives in `index.html`, inside the `<script>` tag:
- `PROJECTS`: the project list (`cat <id>`)
- `SKILLS`: skills and their level (out of 10)
- `LINKS`: GitHub, LinkedIn
- `commands`: the terminal commands (`whoami`, `contact`, `sudo hire-me`…)

Colors are in the `:root` block at the top of the `<style>`.

## To do
- [x] Add the email to `contact`
- [x] Pick the language (English)
- [ ] Replace the ASCII mascot
- [ ] Migrate to React + TypeScript + Tailwind (`My-portfolio` repo)
- [ ] Deploy (GitHub Pages / Netlify / Vercel)
