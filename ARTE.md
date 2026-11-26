# Arte da capa e dos menus

Os quatro menus (Painéis Gerenciais, capa, Jogar e aprender, Apps do dia a dia) seguem o mesmo estilo sóbrio da marca dos Painéis Gerenciais: formas lisas, sem brilho e sem efeito 3D, fundo marfim, e o dourado só como detalhe.

## O que é feito em código e o que é imagem

| Peça | Como é feita |
|---|---|
| Símbolo de cada menu | Em código (vetor), já dentro de cada página e no `favicon.svg`. Não precisa de imagem. |
| Botões | Em código. Incluir um projeto é uma linha no `index.html`. |
| Imagem de fundo | Única peça que vale gerar no ChatGPT. Os prompts estão abaixo. É opcional: sem ela, o fundo é marfim liso. |

A marca dos Painéis Gerenciais (símbolo, assinaturas, ícones, cores e regras) fica no repositório `padroes`, pasta `marca/`.

## Cores

| Uso | Cor |
|---|---|
| Painéis Gerenciais | Vinho `#6e1420` |
| Jogar e aprender | Azul-marinho `#23346b` |
| Apps do dia a dia | Verde-escuro `#1f5244` |
| Textos e apoio | Grafite `#24272e` |
| Detalhe | Dourado fosco `#b0904f` |
| Fundo | Marfim `#f6f3ee` |

## Símbolos

Três deles são feitos de blocos de cantos arredondados, como o símbolo dos Painéis. O dos jogos tem um conceito mais tecnológico, escolhido em 2026-11-26.

- **Capa:** quatro blocos, um de cada cor da família (vinho, azul, verde e dourado).
- **Painéis Gerenciais:** o mosaico da marca, com blocos que sobem como um gráfico.
- **Jogar e aprender:** um dado em 3D feito só de linhas, com os nós em dourado, dentro de um quadrado azul-marinho, como ícone de aplicativo.
- **Apps do dia a dia:** quatro blocos em grade, um deles com o sinal de "feito".

## Prompts dos fundos (para o ChatGPT)

Como usar:

- Anexe a folha da marca (`padroes/marca/folha-da-marca.png`) como referência de estilo.
- Peça em formato paisagem, o mais largo que a ferramenta permitir.
- Salve como `assets/fundo.webp`, com 1920 px de largura e até 300 KB, no repositório do menu.
- O README de cada repositório diz a linha que muda no `index.html`.

### 1. Fundo do menu dos Painéis Gerenciais

```
Imagem de fundo horizontal, em formato paisagem, para uma página de menu. Estilo sóbrio e executivo, minimalista e plano. Fundo marfim claro (#f6f3ee). Composição abstrata de blocos retangulares de cantos levemente arredondados, como papel recortado em camadas, com sombra muito suave. Os blocos ficam alinhados lado a lado e com alturas diferentes, lembrando barras de gráfico e a grade de um painel de indicadores. A maioria dos blocos em tons de marfim e cinza-claro, quase da cor do fundo. Poucos blocos em vinho escuro (#6e1420) e em grafite (#24272e), e um único bloco pequeno em dourado fosco (#b0904f). Os blocos ficam concentrados nos cantos e nas bordas da imagem. O centro fica vazio e liso, para receber botões por cima. Sem brilho, sem reflexo, sem efeito 3D chamativo, sem degradê forte, sem texto, sem letras, sem números, sem pessoas, sem logotipos.
```

### 2. Fundo da capa

```
Imagem de fundo horizontal, em formato paisagem, para uma página de menu. Estilo sóbrio e executivo, minimalista e plano. Fundo marfim claro (#f6f3ee). Composição abstrata de blocos retangulares de cantos levemente arredondados, como papel recortado em camadas, com sombra muito suave. A maioria dos blocos em tons de marfim e cinza-claro, quase da cor do fundo. Três grupos pequenos de blocos coloridos, um em cada região da borda: um grupo em vinho escuro (#6e1420), um em azul-marinho (#23346b) e um em verde-escuro (#1f5244). Um único bloco pequeno em dourado fosco (#b0904f). Os blocos ficam concentrados nos cantos e nas bordas da imagem. O centro fica vazio e liso, para receber botões por cima. Sem brilho, sem reflexo, sem efeito 3D chamativo, sem degradê forte, sem texto, sem letras, sem números, sem pessoas, sem logotipos.
```

### 3. Fundo de "Jogar e aprender"

```
Imagem de fundo horizontal, em formato paisagem, para uma página de menu. Estilo sóbrio, minimalista e plano. Fundo marfim claro (#f6f3ee). Composição abstrata de blocos quadrados de cantos levemente arredondados, como casas de um tabuleiro e peças de jogo, em papel recortado em camadas, com sombra muito suave. Alguns blocos trazem pequenos círculos, como os pontos de um dado. Uma ou duas linhas finas e curvas lembram órbitas de planetas. A maioria dos blocos em tons de marfim e cinza-claro, quase da cor do fundo. Poucos blocos em azul-marinho (#23346b) e em grafite (#24272e), e um único bloco pequeno em dourado fosco (#b0904f). Os elementos ficam concentrados nos cantos e nas bordas da imagem. O centro fica vazio e liso, para receber botões por cima. Sem brilho, sem reflexo, sem efeito 3D chamativo, sem degradê forte, sem texto, sem letras, sem números, sem pessoas, sem logotipos.
```

### 4. Fundo de "Apps do dia a dia"

```
Imagem de fundo horizontal, em formato paisagem, para uma página de menu. Estilo sóbrio, minimalista e plano. Fundo marfim claro (#f6f3ee). Composição abstrata de blocos quadrados de cantos levemente arredondados, dispostos em grade como ícones de aplicativo, em papel recortado em camadas, com sombra muito suave. Alguns blocos trazem linhas finas horizontais, como itens de uma lista, e um deles traz um sinal de "feito". A maioria dos blocos em tons de marfim e cinza-claro, quase da cor do fundo. Poucos blocos em verde-escuro (#1f5244) e em grafite (#24272e), e um único bloco pequeno em dourado fosco (#b0904f). Os elementos ficam concentrados nos cantos e nas bordas da imagem. O centro fica vazio e liso, para receber botões por cima. Sem brilho, sem reflexo, sem efeito 3D chamativo, sem degradê forte, sem texto, sem letras, sem números, sem pessoas, sem logotipos.
```

## Simulação da marca aplicada (opcional)

Serve para apresentar a marca, não como arquivo final. Anexe `padroes/marca/png/assinatura-horizontal.png`.

```
Foto realista e sóbria de um cartão de visita e de um caderno de capa lisa sobre uma mesa de madeira clara, com luz natural suave. Aplique a marca da imagem anexada no cartão e na capa do caderno, sem alterar as formas, as cores, as proporções nem as letras da marca. Paleta do ambiente em marfim, grafite e vinho escuro. Sem outros textos e sem outras marcas.
```
