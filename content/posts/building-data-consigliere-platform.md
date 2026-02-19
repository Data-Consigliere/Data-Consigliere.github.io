---
title: "A Fundação do Data Consigliere: Construindo um Segundo Cérebro Digital"
date: 2024-05-20T10:00:00Z
draft: false
description: "Um mergulho técnico e filosófico na construção deste blog usando Hugo, PaperMod e GitHub Pages."
tags: ["Hugo", "GitHub Pages", "Productivity", "Meta"]
categories: ["Engenharia"]
cover:
    image: "/images/about.jpg" # Ou o nome da sua imagem de destaque
    alt: "Interface do VS Code com código Hugo"
    caption: "Onde a mágica acontece."
---

Na transição de **Analytics tradicional para AI/ML**, a maior barreira não é a falta de informação, mas o excesso dela. Como o "Data Consigliere" do meu próprio percurso, percebi que precisava de um lugar para destilar conceitos, documentar falhas e mapear a curva de aprendizagem.

Este post documenta o primeiro "projeto" desta jornada: a criação desta própria plataforma. 

Inspirado pela filosofia de *Docs as Code*, escolhi um stack que prioriza o controle, a velocidade e a simplicidade: **Hugo, PaperMod e GitHub Pages.**

---

## O Setup: Do Repositório ao Localhost

A escolha do **Hugo** foi pragmática. Como um gerador de sites estáticos (SSG) escrito em Go, ele é ridiculamente rápido. O fluxo de trabalho é simples: escrevo em Markdown, o Hugo compila em HTML puro e o GitHub serve os arquivos.

### 1. O Nascimento no GitHub
Tudo começou com um repositório chamado `Data-Consigliere.github.io`. Este nome é especial no ecossistema do GitHub; ele indica que o site será servido na raiz do domínio.

```bash
git clone [https://github.com/JoseBagina/Data-Consigliere.github.io.git](https://github.com/JoseBagina/Data-Consigliere.github.io.git)
cd Data-Consigliere.github.io
hugo new site . --force

