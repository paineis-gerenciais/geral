# geral

Capa do menu geral: três botões grandes, um para cada menu.

| Botão | Abre |
|---|---|
| Painéis Gerenciais | https://paineis-gerenciais.github.io/menu/ |
| Jogar e aprender | https://paineis-gerenciais.github.io/jogos/ |
| Apps do dia a dia | https://paineis-gerenciais.github.io/apps/ |

Publicação: GitHub Pages → https://paineis-gerenciais.github.io/geral/

## Arquivos

- `index.html` — a capa (HTML + CSS). Os botões e os símbolos são feitos em código, não em imagem. Um trecho curto de JavaScript, no fim do arquivo, sorteia a frase do alto a cada acesso.
- `favicon.svg` — ícone da aba do navegador.
- `ARTE.md` — estilo dos quatro menus, cores e prompts das imagens de fundo.
- `assets/` — criar se for usar imagem de fundo (`fundo.webp`).

## Trocar um texto ou um endereço

Cada botão é um `<li>` em `index.html`. O nome fica em `class="nome"`, a frase em `class="linha"` e o endereço em `href`.
Os endereços são relativos (`../jogos/`): funcionam enquanto os quatro menus estiverem na mesma conta.

## Trocar as frases do alto

As frases ficam na lista `frases`, no fim do `index.html`. Cada acesso sorteia uma.
Para incluir ou tirar uma frase, edite a lista. A primeira também fica escrita no `<h1 id="frase">`: é a que aparece se o JavaScript estiver desligado.

## Colocar a imagem de fundo (opcional)

Sem imagem, o fundo é marfim liso.

1. Gere a imagem com o prompt do `ARTE.md` e salve em `assets/fundo.webp` (1920 px de largura).
2. No alto do `index.html`, troque `--fundo: none;` por `--fundo: url("assets/fundo.webp");`.

Se o fundo ficar forte demais atrás dos botões, aumente o último número de `--veu` (de `.55` para `.75`, por exemplo).
