# Présentation Github copilot Domoti 2024

## Supports de présentation
  1. Slides générées par reveal-js
  2. fichiers pour démonstration code live dans le dossier ../copilot-live

### Les slides

> Les slides sont disponible au format github-pages. Cette présentation est ouverte à la modification.

#### Démarrer les Slides en mode développement (nvm use 18)
> Pour modifier - ajouter des slides

```bash
npm i
npm start
# Server started http://localhost:8000 livereload 🎉
```

#### Accès aux slides

Accéder aux slides via gh-pages → ton browser préféré → Goto [manuelweb.github.io](https://manuelweb.github.io/)

#### collaborer 🙏 deux solutions :
Prérequis un compte Github
1. fork + Pull request
2. passe moi ton compte Github je t'envoi une invitation

### La démo live

> fichiers js - ts pour du live coding. Les démos sont listé au fil les slides


# Tech note

## NVM

### Changer la node -v avec cd rep

> Le fichier .nvmrc est un fichier qui contient la version de Node.js à utiliser dans un projet. Il est utilisé par nvm pour changer de version de Node.js lorsque vous entrez dans un répertoire.

Ajouter ce code dans le fichier .bashrc ou .zshrc

```bash
# Fonction pour changer de version Node.js en utilisant .nvmrc
nvm_auto_switch() {
  if [[ -f ".nvmrc" ]]; then
    nvm use
  fi
}

# Appeler la fonction lorsque vous entrez dans un répertoire
cd() {
  builtin cd "$@" && nvm_auto_switch
}
```

# reveal.js

<p align="center">
  <a href="https://revealjs.com">
  <img src="https://hakim-static.s3.amazonaws.com/reveal-js/logo/v1/reveal-black-text-sticker.png" alt="reveal.js" width="500">
  </a>
  <br><br>
  <a href="https://github.com/hakimel/reveal.js/actions"><img src="https://github.com/hakimel/reveal.js/workflows/tests/badge.svg"></a>
  <a href="https://slides.com/"><img src="https://s3.amazonaws.com/static.slid.es/images/slides-github-banner-320x40.png?1" alt="Slides" width="160" height="20"></a>
</p>

reveal.js is an open source HTML presentation framework. It enables anyone with a web browser to create beautiful presentations for free. Check out the live demo at [revealjs.com](https://revealjs.com/).

The framework comes with a powerful feature set including [nested slides](https://revealjs.com/vertical-slides/), [Markdown support](https://revealjs.com/markdown/), [Auto-Animate](https://revealjs.com/auto-animate/), [PDF export](https://revealjs.com/pdf-export/), [speaker notes](https://revealjs.com/speaker-view/), [LaTeX typesetting](https://revealjs.com/math/), [syntax highlighted code](https://revealjs.com/code/) and an [extensive API](https://revealjs.com/api/).

---

Want to create reveal.js presentation in a graphical editor? Try <https://slides.com>. It's made by the same people behind reveal.js.

---

### Sponsors

Hakim's open source work is supported by <a href="https://github.com/sponsors/hakimel">GitHub sponsors</a>. Special thanks to:
<div align="center">
  <table>
    <td align="center">
      <a href="https://workos.com/?utm_campaign=github_repo&utm_medium=referral&utm_content=revealjs&utm_source=github">
        <div>
          <img src="https://user-images.githubusercontent.com/629429/151508669-efb4c3b3-8fe3-45eb-8e47-e9510b5f0af1.svg" width="290" alt="WorkOS">
        </div>
        <b>Your app, enterprise-ready.</b>
        <div>
          <sub>Start selling to enterprise customers with just a few lines of code. Add Single Sign-On (and more) in minutes instead of months.</sup>
        </div>
      </a>
    </td>
  </table>
</div>

---

### Getting started

- 🚀 [Install reveal.js](https://revealjs.com/installation)
- 👀 [View the demo presentation](https://revealjs.com/demo)
- 📖 [Read the documentation](https://revealjs.com/markup/)
- 🖌 [Try the visual editor for reveal.js at Slides.com](https://slides.com/)
- 🎬 [Watch the reveal.js video course (paid)](https://revealjs.com/course)

---
<div align="center">
  MIT licensed | Copyright © 2011-2024 Hakim El Hattab, https://hakim.se
</div>
