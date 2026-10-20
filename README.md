<div align="center">
  <img src="assets/visagi-icone.svg" width="96" height="96" alt="Visagi" />

  <h1>Visagi · Site</h1>

  <p><strong>Seu estilo, calculado.</strong></p>

  <p>
    <a href="https://douglasproglima.github.io/visagi-site/">
      <img src="https://img.shields.io/badge/PT--BR-ACESSAR_SITE-D97706?style=for-the-badge" alt="Acessar o site em português" />
    </a>
    &nbsp;
    <a href="https://douglasproglima.github.io/visagi-site/en/">
      <img src="https://img.shields.io/badge/EN-VISIT_SITE-B45309?style=for-the-badge" alt="Visit the site in English" />
    </a>
  </p>

  <p>
    <img src="https://img.shields.io/github/deployments/Douglasproglima/visagi-site/github-pages?label=github%20pages&style=flat-square&color=10B981" alt="Status do GitHub Pages" />
    <img src="https://img.shields.io/badge/Licença-privada-161B22?style=flat-square" alt="Licença privada" />
    <img src="https://img.shields.io/badge/stack-HTML%20%2B%20CSS-9AA4B2?style=flat-square" alt="Stack: HTML + CSS" />
  </p>
</div>

<br>

Site estático de marketing do [Visagi](https://github.com/Douglasproglima/visagi), em português e inglês.

---

## O que é

Uma página só, duas vezes: [`index.html`](index.html) em português (padrão) e [`en/index.html`](en/index.html) em inglês. Sem build tool, sem framework, sem dependência de JavaScript além do alternador de tema.

## Estrutura

```
visagi-site/
├── index.html      pt-BR (padrão)
└── en/
    └── index.html  inglês
```

Cada página é autocontida: CSS e JavaScript inline, ícone embutido como SVG em data URI. Nenhuma imagem externa.

## Fonte de verdade

Este repositório é público e não contém código nem documentação interna do app. Qualquer afirmação factual sobre o produto vem do repositório privado [`visagi`](https://github.com/Douglasproglima/visagi), principalmente:

| Arquivo (no repo `visagi`) | O quê |
|---|---|
| `.claude/rules/dominio-visagismo.md` | Contrato de domínio, vocabulário fechado, regra de promessa |
| `.claude/rules/writing-style.md` | Estilo de escrita, mesma regra de sem travessão |
| `docs/branding/identidade-visual.md` | Paleta, tipografia, logo |
| `docs/branding/tom-de-voz.md` | Tom de voz, pares "não escrever / escrever" |
| `design-tokens/*.tokens.json` | Valores de cor exatos |

Não inventar afirmação nova aqui. Ver [`CLAUDE.md`](CLAUDE.md) para o detalhe completo.

## Pendências conhecidas

Dois trechos do texto usam placeholder, de propósito, enquanto a decisão real não existe:

- `[NOME DO PROVEDOR]` / `[PAÍS/REGIÃO]`: depende do provedor de nuvem (issue [#16](https://github.com/Douglasproglima/visagi/issues/16) do repositório `visagi`).
- `[MODELO DE PREÇO]`: nenhuma decisão de modelo de negócio foi tomada ainda.

## Publicação

GitHub Pages direto deste repositório (já é público). Qualquer mudança em `main` reflete no site.

---

<div align="center">
<sub>Douglas Lima · Brasil · pt-BR / en</sub>
</div>
