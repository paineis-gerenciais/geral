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
- `assets/fundo.webp` — imagem de fundo.

## Trocar um texto ou um endereço

Cada botão é um `<li>` em `index.html`. O nome fica em `class="nome"`, a frase em `class="linha"` e o endereço em `href`.
Os endereços são relativos (`../jogos/`): funcionam enquanto os quatro menus estiverem na mesma conta.

## Trocar as frases do alto

As frases ficam na lista `frases`, no fim do `index.html`. Cada acesso sorteia uma.
Para incluir ou tirar uma frase, edite a lista. A primeira também fica escrita no `<h1 id="frase">`: é a que aparece se o JavaScript estiver desligado.

## Imagem de fundo

O fundo é a imagem `assets/fundo.webp`, com um véu marfim por cima para não disputar com os botões. O prompt que gerou a imagem está no `ARTE.md` do repositório `geral`.

- **Trocar a imagem:** salve a nova por cima de `assets/fundo.webp` (1920 px de largura, até 300 KB).
- **Clarear ou escurecer:** no alto do `index.html`, mude o último número de `--veu`. Mais perto de `1` clareia; mais perto de `0` mostra mais a imagem.
- **Tirar a imagem:** no alto do `index.html`, troque o valor de `--fundo` por `none`. O fundo volta ao marfim liso.
