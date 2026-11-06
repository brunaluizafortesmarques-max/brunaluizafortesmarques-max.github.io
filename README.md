# Portfólio · Bruna Marques

Site pessoal publicado com GitHub Pages: [brunaluizafortesmarques-max.github.io](https://brunaluizafortesmarques-max.github.io/)

> **English summary:** Personal portfolio site, plain HTML and CSS with no build step, hosted on GitHub Pages. Accessible (semantic landmarks, skip link, visible focus, reduced-motion support, AA contrast) and machine-readable (schema.org `Person` JSON-LD).

## Tecnologias

- HTML5 semântico e CSS3 (grid, flexbox, `clamp()`, media queries), sem frameworks e sem etapa de build
- Dados estruturados schema.org (JSON-LD) para buscadores e ferramentas de triagem com IA
- GitHub Pages

## Acessibilidade

- Link "Pular para o conteúdo" e regiões `header`, `nav`, `main` e `footer`
- Hierarquia de títulos sem saltos e cada seção ligada ao seu título (`aria-labelledby`)
- Foco visível em todos os links e botões
- Contraste de texto acima de 4,5:1 sobre o fundo escuro
- Respeita `prefers-reduced-motion`
- Layout responsivo, sem rolagem horizontal em 375 px
- Elementos decorativos marcados com `aria-hidden`

## Como rodar localmente

```bash
python -m http.server 8000
```

Depois abra `http://localhost:8000`.

## Publicar

O repositório se chama `brunaluizafortesmarques-max.github.io`, então o GitHub Pages publica a branch `main` automaticamente na raiz. Se não aparecer, ative em **Settings → Pages → Deploy from a branch → main / (root)**.
