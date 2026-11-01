# root@farah — portfolio terminal

Portfolio de Farah Grissa au style terminal Linux (palette néon rose, violet et cyan).

## Lancer en local
Ouvre simplement `index.html` dans ton navigateur (double-clic), ou :

```bash
python -m http.server 8000   # puis http://localhost:8000
```

## Modifier le contenu
Tout est dans `index.html`, dans la balise `<script>` :
- `PROJECTS` : la liste des projets (`cat <id>`)
- `SKILLS` : les compétences et leur niveau (sur 10)
- `LINKS` : GitHub, LinkedIn
- `commands` : les commandes du terminal (`whoami`, `contact`, `sudo hire-me`…)

Les couleurs sont dans le bloc `:root` en haut du `<style>`.

## À faire
- [ ] Ajouter l'e-mail dans `contact`
- [ ] Choisir la langue (FR / EN / commande `lang`)
- [ ] Remplacer la mascotte ASCII
- [ ] Migrer vers React + TypeScript + Tailwind (dépôt `My-portfolio`)
- [ ] Déployer (GitHub Pages / Netlify / Vercel)
