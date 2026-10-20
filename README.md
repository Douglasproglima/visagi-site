<div align="center">

# Visagi · Site

**Seu estilo, calculado.**

Site estático de marketing do [Visagi](https://github.com/Douglasproglima/visagi), em português e inglês.

[![Site](https://img.shields.io/badge/site-douglasproglima.github.io%2Fvisagi--site-D97706?logo=googlechrome&logoColor=white)](https://douglasproglima.github.io/visagi-site/)
[![Licença](https://img.shields.io/badge/Licença-privada-161B22)](#)

**🔗 [douglasproglima.github.io/visagi-site](https://douglasproglima.github.io/visagi-site/)**

</div>

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
