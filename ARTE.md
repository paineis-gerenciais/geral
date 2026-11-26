# Arte da capa e dos menus Jogos e Apps

Sugestão de arte e prompts para gerar os símbolos e as imagens de fundo.
As páginas já funcionam sem essas imagens: hoje usam símbolos desenhados em código e um fundo liso.

## Ideia geral

Os três menus novos são da mesma família do menu dos Painéis Gerenciais:
emblema 3D brilhante com borda dourada, fundo claro com formas de vidro e botões escuros com filete de ouro.
O que muda de um menu para o outro é a cor.

| Página | Cor principal | Símbolo | Fundo |
|---|---|---|---|
| Capa (`geral`) | as três cores juntas, sobre marfim | escudo com três facetas: vinho, azul e verde | painéis de vidro nas três cores, com um gráfico, um dado e blocos de app ao longe |
| Jogar e aprender (`jogos`) | azul-royal `#2f45b8` e azul-noite `#111a55` | dado azul com um anel de órbita dourado (jogo + ciência) | dado, peças de tabuleiro, torre de castelo, bola de futebol americano e planeta com anel |
| Apps do dia a dia (`apps`) | verde-esmeralda `#12825f` e verde-escuro `#073f31` | quatro blocos arredondados, um deles com um "feito" | panela, cesta de compras, alfinete de mapa, prancheta e gráfico de pizza |
| Painéis Gerenciais (`menu`, já existe) | vinho `#8b0a0a` | escudo com gráfico (logo atual) | fundo atual |

O ouro `#d4a24c` aparece em todas as páginas e é o que amarra a família.

O escudo da capa repete a forma do escudo da logo dos Painéis Gerenciais. Assim a capa "contém" os três menus, e os Painéis continuam com a logo deles.

## Como gerar

- Anexe a logo e o fundo atuais dos Painéis Gerenciais (`menu/assets/logo.webp` e `menu/assets/fundo.webp`) como referência de estilo, se a ferramenta aceitar imagem de referência.
- Nenhuma imagem leva texto. Os títulos e os nomes dos botões são escritos pela página.
- Gere cada prompt separado. Todos já trazem a descrição completa do estilo.

| Imagem | Formato ao gerar | Como salvar |
|---|---|---|
| Símbolo | quadrado, 1024 × 1024, fundo transparente | `assets/simbolo.webp`, com 512 px de lado |
| Fundo | paisagem 16:9, cerca de 2400 × 1350 | `assets/fundo.webp`, com 1920 px de largura e até 300 KB |

Cada repositório (`geral`, `jogos`, `apps`) recebe o seu par de imagens na pasta `assets/`. O README de cada um diz as duas linhas que mudam no `index.html`.

## Prompts dos símbolos

### 1. Símbolo da capa

```
Emblema 3D brilhante em forma de escudo, estilo logotipo corporativo premium. O escudo é dividido em três facetas esmaltadas: vermelho-vinho escuro no alto à esquerda, azul-royal no alto à direita e verde-esmeralda na parte de baixo, separadas por filetes finos de ouro polido. Borda larga do escudo em ouro polido com chanfro. Superfícies lisas com reflexos suaves, luz de estúdio vinda do alto à esquerda, sombra suave embaixo. Vista frontal, centralizado, com margem em volta. Fundo transparente. Sem texto, sem letras, sem números, sem pessoas.
```

### 2. Símbolo de "Jogar e aprender"

```
Emblema 3D brilhante, estilo logotipo corporativo premium: um dado de jogo com cantos bem arredondados, em esmalte azul-royal com degradê para azul-noite, levemente inclinado, com os pontos e a borda em ouro polido. Um anel fino de órbita, também em ouro, passa em volta do dado, com uma pequena esfera dourada presa ao anel, como um planeta e sua lua. Superfícies lisas com reflexos suaves, luz de estúdio vinda do alto à esquerda, sombra suave embaixo. Vista frontal, centralizado, com margem em volta. Fundo transparente. Sem texto, sem letras, sem números, sem pessoas.
```

### 3. Símbolo de "Apps do dia a dia"

```
Emblema 3D brilhante, estilo logotipo corporativo premium: quatro blocos quadrados de cantos bem arredondados, dispostos em grade dois por dois, como ícones de aplicativo. Três blocos em esmalte verde-esmeralda com degradê para verde-escuro. O quarto bloco, embaixo à direita, é branco perolado e traz um sinal de "feito" (check) em verde-esmeralda. Todos com borda em ouro polido com chanfro. Superfícies lisas com reflexos suaves, luz de estúdio vinda do alto à esquerda, sombra suave embaixo. Vista frontal, centralizado, com margem em volta. Fundo transparente. Sem texto, sem letras, sem números, sem pessoas.
```

## Prompts dos fundos

### 4. Fundo da capa

```
Imagem de fundo horizontal 16:9, muito clara e suave, em tons de branco e marfim. Formas 3D de vidro translúcido e acrílico fosco, concentradas nas bordas e nos cantos: painéis curvos e arcos em três cores discretas, vermelho-vinho, azul-royal e verde-esmeralda, com filetes finos de ouro polido. Ao longe e desfocados, três objetos pequenos de vidro: um gráfico de barras vinho, um dado azul e uma grade de blocos verdes. O centro da imagem fica vazio e limpo, quase branco, para receber botões por cima. Luz difusa, profundidade de campo rasa, acabamento elegante e corporativo. Sem texto, sem letras, sem pessoas, sem logotipos.
```

### 5. Fundo de "Jogar e aprender"

```
Imagem de fundo horizontal 16:9, muito clara e suave, em tons de branco e azul bem pálido. Formas 3D de vidro translúcido e acrílico fosco em azul-royal, com filetes finos de ouro polido, concentradas nas bordas e nos cantos: um dado, peças de tabuleiro, uma torre de castelo, uma bola de futebol americano e um planeta com anel e pequenas luas em órbita. Arcos finos dourados lembram órbitas. O centro da imagem fica vazio e limpo, quase branco, para receber botões por cima. Luz difusa, profundidade de campo rasa, acabamento elegante. Sem texto, sem letras, sem números, sem pessoas, sem logotipos.
```

### 6. Fundo de "Apps do dia a dia"

```
Imagem de fundo horizontal 16:9, muito clara e suave, em tons de branco e verde bem pálido. Formas 3D de vidro translúcido e acrílico fosco em verde-esmeralda, com filetes finos de ouro polido, concentradas nas bordas e nos cantos: uma panela com vapor, uma cesta de compras, um alfinete de mapa, uma prancheta com lista marcada e um gráfico de pizza. Arcos finos dourados ligam os objetos. O centro da imagem fica vazio e limpo, quase branco, para receber botões por cima. Luz difusa, profundidade de campo rasa, acabamento elegante e acolhedor. Sem texto, sem letras, sem números, sem pessoas, sem logotipos.
```

## Extra: botão da calculadora no menu dos Painéis

O menu dos Painéis usa botões em imagem. Para a calculadora entrar lá, falta a arte deste botão.
Anexe um botão atual (por exemplo `menu/assets/btn-matriz-risco.webp`) como referência.

```
Botão horizontal na proporção 3:1, no mesmo estilo da imagem de referência: fundo vermelho-vinho escuro brilhante com degradê, borda fina em ouro, arco dourado no canto inferior direito. À esquerda, um quadro de cantos arredondados com um ícone dourado de escada de degraus subindo com uma seta para cima. Um traço vertical dourado separa o ícone do texto. À direita, o texto em duas linhas: "Simulador de" em branco, menor, e "Carreiras" em dourado, maior e em negrito. Mesma fonte, mesmas proporções e mesmo brilho da referência. Fundo transparente fora do botão.
```

Salvar como `btn-simulador-carreiras.webp`, com 720 × 240 px.
