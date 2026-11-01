# root@farah — terminal portfolio

An interactive portfolio styled as a Linux terminal, with a neon pink, violet and cyan palette. Type commands to explore my projects, skills and contact info.

**Live demo:** https://farahgrissa.github.io/root-farah/

## Features

- Interactive shell: type commands and get answers, just like a real terminal
- Projects, skills and links all browsable from the prompt
- Single file, no build step, no dependencies
- Easy to customize: content and colors live in one place

## Available commands

| Command | What it does |
|---|---|
| `whoami` | Short introduction |
| `cat <id>` | Details of a project |
| `contact` | Email and social links |
| `sudo hire-me` | Try it 😉 |

## Run locally

Open `index.html` in your browser (double-click), or serve it:

```bash
python -m http.server 8000
# then open http://localhost:8000
```

## Customize

Everything lives in `index.html`, inside the `<script>` tag:

- `PROJECTS`: the project list, shown with `cat <id>`
- `SKILLS`: skills and their level (out of 10)
- `LINKS`: GitHub and LinkedIn
- `commands`: the terminal commands and their output

Colors are defined in the `:root` block at the top of the `<style>` tag.

## Tech

HTML, CSS and vanilla JavaScript. Deployed with GitHub Pages.

## Author

**Farah Grissa** — final-year computer science engineering student (artificial intelligence), interested in DevSecOps, cloud and AI agents.
GitHub: [@Farahgrissa](https://github.com/Farahgrissa)