---
layout: post
title: "Como publiquei meu site com GitHub Pages"
date: 2025-04-26 12:30:00 +0000
categories: blog
tags: [github-pages, jekyll, markdown]
---

# 🚀 Como publiquei meu site com GitHub Pages

Este é o primeiro post do meu blog técnico e faz parte do meu portfólio `ThRoot - HomeLab & Cybersecurity Journey`.

Neste artigo, explico de forma direta como subi meu site no GitHub Pages usando o tema `just-the-docs` com domínio personalizado (`lab.throot.com.br`).

---

## 🔧 Passos realizados

1. Criei o repositório `lab.throot.com.br` no GitHub.
2. Clonei para minha máquina e organizei a estrutura inicial (`index.md`, `_config.yml`, `_sidebar.yml`, `docs/`).
3. Criei o arquivo `CNAME` com o domínio personalizado.
4. Configurei o domínio e DNS via Hostinger.
5. Executei o push com os comandos:

```bash
git init
git remote add origin https://github.com/0xThiagoAmaral/lab.throot.com.br.git
git branch -M main
git add .
git commit -m "🚀 Primeiro commit - Estrutura inicial do site"
git push -u origin main
```

6. Criei esta pasta `_posts/` com este primeiro artigo para meu blog.

---

## 📚 Por que isso é importante?

Documentar em tempo real o que aprendo é minha forma de consolidar o conhecimento, treinar comunicação técnica e criar autoridade pública.

Este blog será minha vitrine prática enquanto avanço nos estudos de cibersegurança.

---

**🔗 Acesse:** [https://lab.throot.com.br](https://lab.throot.com.br)
