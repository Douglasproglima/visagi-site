# Visagi Site: Instruções do Projeto

Site estático de marketing do Visagi (app de visagismo masculino). Só isso: sem backend, sem build tool, sem framework. Uma página em `index.html` (português) e a mesma página em `en/index.html` (inglês).

## Fonte de verdade

Este repositório é público e não contém código nem documentação interna do app. Qualquer afirmação factual sobre o produto (contrato de 3 fotos, 7 formatos de rosto, as 3 trilhas, regra de promessa, tom de voz) vem do repositório privado `Douglasproglima/visagi`, principalmente:

- `.claude/rules/dominio-visagismo.md`: contrato de domínio, vocabulário fechado, regra de promessa.
- `.claude/rules/writing-style.md`: estilo de escrita, mesma regra de sem travessão.
- `docs/branding/identidade-visual.md` e `docs/branding/tom-de-voz.md`: paleta, tipografia, tom.
- `design-tokens/*.tokens.json`: valores de cor exatos.

Não inventar afirmação nova aqui. Se o repositório `visagi` não documenta algo, ou não escrever, ou perguntar antes.

## Placeholder é placeholder

`[NOME DO PROVEDOR]`, `[PAÍS/REGIÃO]`, `[MODELO DE PREÇO]` no texto são propositais, não esquecimento. Preencher só quando a decisão real existir no repositório `visagi` (issues #16 e modelo de negócio). Nunca inventar um valor plausível pra esses campos.

## Dois idiomas, uma fonte

`index.html` (pt-BR) é a versão principal. `en/index.html` é tradução, não reescrita: mesma estrutura, mesmas seções, mesmo tom. Mudou uma frase num idioma por causa de uma correção de fato (não só de tradução), mudar no outro na mesma alteração.

## Escrita

Mesma regra do projeto principal: frases curtas, sem travessão (`—`) nem hífen duplo (`--`) colando duas ideias, sem elogio vago, sem linguagem de promessa que o produto não cumpre (nunca "corte perfeito", "transformação radical", "cientificamente comprovado"). Rodar `grep -rn "—\|--" *.html en/*.html` antes de considerar um texto pronto.

## Git

Mesmo padrão do repositório `visagi`: commit de uma linha, minúsculo, sem acento no assunto, sem coautor, prefixo `feat`, `fix`, `chore` ou `content` (textos/copy). Branch direto em `main` para mudança pequena de conteúdo; branch nomeada para mudança estrutural. Nunca fazer push nem mudar configuração do GitHub Pages sem confirmação explícita.
