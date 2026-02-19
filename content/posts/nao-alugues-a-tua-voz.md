---
title: "Não Alugues a Tua Voz"
date: 2024-05-20T10:00:00Z
draft: false
description: "Por que construí este blog do zero — e o que isso tem a ver com a forma como penso sobre dados, decisões e autonomia."
tags: ["Meta", "Hugo", "GitHub Pages", "Filosofia"]
categories: ["Engenharia"]
cover:
    image: "/images/about.jpg"
    alt: "Terminal com comandos Hugo"
    caption: "Onde começa a autonomia."
---

Há uma distinção que aprendi a fazer — não em código, mas em negócio — entre **activos** e **canais alugados**.

Um canal alugado é rápido. Dás uma plataforma os teus melhores pensamentos, ela amplifica-os enquanto lhe convém, e um dia muda o algoritmo, as condições de serviço, ou simplesmente fecha. O Medium pode restringir leituras. O Substack pode mudar o modelo de negócio. O LinkedIn pode decidir que o teu conteúdo compete com o deles.

Não tenho nada contra essas plataformas. Mas não quero *alugar* a minha voz.

O **Data Consigliere** existe aqui, neste domínio, gerado por código que controlo, publicado numa infraestrutura que compreendo. Não por purismo técnico — por princípio estratégico.

---

## O Problema com "Começar Rápido"

Quando alguém com trinta anos de experiência em Analytics decide criar presença digital, a recomendação padrão é sempre a mesma: *usa uma plataforma pronta, não percas tempo com infraestrutura.*

É um conselho razoável para a maioria. Para mim, era exactamente o problema.

Trabalho com dados há décadas. Sei o que acontece quando uma organização constrói os seus processos críticos sobre sistemas que não controla: fica refém. Paga royalties. Perde agilidade. E quando quer mudar, o custo de migração é proibitivo.

Não ia fazer o mesmo com o meu próprio pensamento.

---

## A Escolha do Stack: Minimalismo como Postura

A escolha foi deliberada e rápida: **Hugo** como gerador de sites estáticos, **PaperMod** como tema, **GitHub Pages** como infraestrutura.

Porquê?

O Hugo é escrito em Go. Compila um site com centenas de posts em menos de um segundo. Não há base de dados, não há servidor a gerir, não há vulnerabilidades a patchar. É um binário. Funciona.

O PaperMod é a escolha de quem respeita o leitor: limpo, rápido, com modo escuro impecável. Não há carrosséis de imagens, não há pop-ups de newsletter, não há distrações. O texto é o produto.

O GitHub Pages serve ficheiros estáticos gratuitamente, com HTTPS, com redundância global. É a infraestrutura mais simples possível para o que preciso.

O fluxo de trabalho que resulta disto é o seguinte: escrevo em Markdown no VS Code, faço `git push`, e o site está online. É o modelo *Docs as Code* aplicado ao pensamento pessoal.

---

## O que as Máquinas Não Te Contam (e os Humanos Também Não)

O deploy inicial foi uma lição de humildade clássica — o tipo que só aprende quem põe as mãos na massa.

**Case sensitivity não é teórica.** No meu ambiente Windows, `About.jpg` e `about.jpg` são a mesma coisa. No servidor Linux do GitHub, não são. O erro 404 que me perseguiu durante horas tinha uma causa absurdamente simples: capitalização inconsistente nos nomes de ficheiros. A lição não é técnica — é sobre assumir que o ambiente de produção vai ser diferente do teu ambiente de desenvolvimento. Sempre. Regra: tudo em minúsculas, para sempre.

**O GitHub Pages não é um servidor passivo.** Por omissão, tenta processar o site com Jekyll — o seu próprio gerador. Para um site Hugo, isso é um desastre silencioso. A solução é um ficheiro vazio chamado `.nojekyll` na raiz do repositório. Um ficheiro vazio. Que faz toda a diferença. Há uma metáfora aqui sobre burocracia organizacional, mas deixo para outro dia.

**Integridade tem custos.** O Hugo gera um hash criptográfico do CSS por questões de segurança. Se o ficheiro for modificado durante o upload — mesmo que por um byte — o browser bloqueia o carregamento. A solução foi desactivar o fingerprinting. Aprendi que segurança máxima e pragmatismo operacional raramente coexistem sem negociação.

---

## O que Este Blog Não É

Não é um tutorial. Não é um repositório de certezas. Não é o palco de um guru que chegou a algum lado e vem distribuir sabedoria.

É o caderno de campo de alguém em trânsito. Da Analytics tradicional para Engenharia de Dados e AI/ML. De executar análises para arquitectar sistemas. De consumir dados para os governar.

O nome **Data Consigliere** não é uma pose. É uma postura. O consigliere não grita. Não vende. Fala com precisão para quem precisa de clareza — não de ruído. Serve os líderes que têm de tomar decisões difíceis com informação imperfeita. Conhece o campo inteiro, não apenas a sua peça.

É essa a ambição.

---

## A Fundação Está Sólida

O site está online. O fluxo de trabalho funciona. A voz está a começar a tomar forma.

O próximo passo é o que realmente importa: deixar de falar sobre a ferramenta e começar a usar a ferramenta para falar sobre o que interessa — dados, decisões, arquitecturas, e as escolhas que definem a diferença entre sistemas que servem e sistemas que aprisionam.

Se estás a ler isto, chegaste cedo. Isso é bom sinal para ti.

---

*O Data Consigliere é publicado em [data-consigliere.github.io](https://data-consigliere.github.io). Sem algoritmos a satisfazer. Sem métricas de engagement a optimizar. Apenas pensamento estruturado, publicado com consistência.*
