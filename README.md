# Exercício 4 - CSS (Externo, Interno e Inline)

Este exercício **dá continuidade ao arquivo do Exercício 3** (mesmo
`index.html`, mesmas seções e mesma folha `css/style.css`), apenas
acrescentando o que o Exercício 4 pede.

## Objetivo

Redefinir o estilo de tags HTML, criar novas classes e ids, e aplicá-los
usando as três formas de CSS.

## O que foi acrescentado ao arquivo do Exercício 3

- **Tags redefinidas** (novas, no final de `css/style.css`):
  `blockquote`, `hr`, `code`, `mark`.
- **Novas classes**: `.card`, `.card-destaque`, `.tabela-fit`, `.btn-cta`.
- **Novos ids**: `#contato-rapido`, `#imc`.

## Onde cada forma de CSS aparece

- **Externo** (`css/style.css`): toda a folha herdada do Exercício 3,
  mais as regras novas listadas acima.
- **Interno** (`<style>` no `<head>` do `index.html`): regra específica
  desta página para o selo "Exercício 4" (`.selo-novo`) e para o
  destaque da seção `#imc`.
- **Inline** (atributo `style` na própria tag): no parágrafo de contato
  por e-mail, dentro da seção "Recursos e Contatos".

## Como abrir

Abra `index.html` no navegador ou use a extensão Live Server no VS Code.
