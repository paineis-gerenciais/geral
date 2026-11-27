# Arte da capa e dos menus

Os quatro menus (Painéis Gerenciais, capa, Jogar e aprender, Apps do dia a dia) seguem o mesmo estilo sóbrio da marca dos Painéis Gerenciais: formas lisas, sem brilho e sem efeito 3D, fundo marfim, e o dourado só como detalhe.

## O que é feito em código e o que é imagem

| Peça | Como é feita |
|---|---|
| Símbolo de cada menu | Em código (vetor), já dentro de cada página e no `favicon.svg`. Não precisa de imagem. |
| Botões | Em código. Incluir um projeto é uma linha no `index.html`. |
| Imagem de fundo | Única peça gerada no ChatGPT, com os prompts abaixo. As quatro imagens foram aplicadas em 2026-11-27 (`assets/fundo.webp` na capa, nos jogos e nos apps; `assets/fundo-sobrio.webp` no menu dos Painéis). |

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

Cada prompt pede elementos ligados aos projetos daquele menu e usa a folha da marca do grupo como referência.

Como usar:

- Anexe a folha da marca indicada em cada prompt. Ela dá o estilo e as cores.
- Peça em formato paisagem, o mais largo que a ferramenta permitir.
- Se os elementos saírem fortes demais, peça em seguida: "Deixe os elementos mais claros e o centro ainda mais vazio".
- Salve com 1920 px de largura e até 300 KB. O README de cada repositório diz o nome do arquivo e a linha que muda no `index.html`.

### 1. Fundo do menu dos Painéis Gerenciais

Anexar: `padroes/marca/folha-da-marca.png`.
Elementos ligados a: Gestão de Projetos, Organograma, Processos, Matriz de Risco, Cadeia de Valor e Simulador de Carreiras.

```
Use a folha da marca anexada só como referência de estilo e de cores: formas lisas, cantos levemente arredondados, sem brilho e sem efeito 3D. Não copie a folha e não reproduza o símbolo, o nome nem nenhum texto dela.

Crie uma imagem de fundo horizontal, em formato paisagem, para uma página de menu, em estilo sóbrio, minimalista e plano. Fundo marfim claro (#f6f3ee). A imagem traz, de forma discreta, elementos do trabalho de gestão: barras de gráfico de alturas diferentes; um organograma de caixas ligadas por linhas finas; um fluxo de processo, com caixas e setas; uma grade de três por três casas, como uma matriz de risco; setas em forma de divisa, lado a lado, como uma cadeia de valor; e degraus subindo, como uma carreira.

Os desenhos são simples e planos, como papel recortado em camadas, com sombra muito suave. A maior parte deles fica em tons de marfim e cinza-claro, quase da cor do fundo. Poucos elementos em vinho escuro (#6e1420) e em grafite (#24272e), e um único detalhe pequeno em dourado fosco (#b0904f). Os elementos ficam concentrados nos cantos e nas bordas da imagem, alguns cortados pela borda. O centro fica vazio e liso, para receber botões por cima. Sem brilho, sem reflexo, sem efeito 3D chamativo, sem degradê forte, sem texto, sem letras, sem números, sem pessoas, sem logotipos.
```

### 2. Fundo da capa

Anexar as três folhas: `padroes/marca/folha-da-marca.png`, `jogos/marca/folha-da-marca.png` e `apps/marca/folha-da-marca.png`.
Elementos ligados a: um pouco de cada menu, cada grupo na sua cor.

```
Use as três folhas de marca anexadas só como referência de estilo e de cores: formas lisas, cantos levemente arredondados, sem brilho e sem efeito 3D. Não copie as folhas e não reproduza os símbolos, os nomes nem nenhum texto delas.

Crie uma imagem de fundo horizontal, em formato paisagem, para uma página de menu, em estilo sóbrio, minimalista e plano. Fundo marfim claro (#f6f3ee). A imagem traz três grupos discretos de elementos, um em cada região da borda. À esquerda, em vinho escuro (#6e1420): barras de gráfico e um organograma de caixas ligadas por linhas. Em cima, à direita, em azul-marinho (#23346b): um dado em perspectiva desenhado só com linhas e uma torre de castelo. Embaixo, à direita, em verde-escuro (#1f5244): blocos em grade como ícones de aplicativo, uma panela e um alfinete de mapa.

Os desenhos são simples e planos, como papel recortado em camadas, com sombra muito suave. A maior parte deles fica em tons de marfim e cinza-claro, quase da cor do fundo. Em cada grupo, só um ou dois elementos levam a cor do grupo. Há um único detalhe pequeno em dourado fosco (#b0904f) na imagem toda. Os elementos ficam concentrados nos cantos e nas bordas da imagem, alguns cortados pela borda. O centro fica vazio e liso, para receber botões por cima. Sem brilho, sem reflexo, sem efeito 3D chamativo, sem degradê forte, sem texto, sem letras, sem números, sem pessoas, sem logotipos.
```

### 3. Fundo de "Jogar e aprender"

Anexar: `jogos/marca/folha-da-marca.png`.
Elementos ligados a: FA Manager, Torres do Reino, Quadra, Órbitas, Rachess e Bancada, além do dado do símbolo.

```
Use a folha da marca anexada só como referência de estilo e de cores: formas lisas, cantos levemente arredondados, sem brilho e sem efeito 3D. Não copie a folha e não reproduza o símbolo, o nome nem nenhum texto dela.

Crie uma imagem de fundo horizontal, em formato paisagem, para uma página de menu, em estilo sóbrio, minimalista e plano. Fundo marfim claro (#f6f3ee). A imagem traz, de forma discreta, elementos de jogos e de ciência: uma bola de futebol americano; uma torre de castelo; uma grade de quatro por quatro cartões em branco; um planeta com anéis de órbita em linhas finas; peças de xadrez, como um peão e um cavalo; um frasco de laboratório e um pêndulo; e um dado em perspectiva, desenhado só com linhas e com pequenos nós nos cantos. Alguns desses elementos são formas cheias e outros são desenhos só de linhas finas, como modelos de computador.

Os desenhos são simples e planos, como papel recortado em camadas, com sombra muito suave. A maior parte deles fica em tons de marfim e cinza-claro, quase da cor do fundo. Poucos elementos em azul-marinho (#23346b) e em grafite (#24272e), e alguns nós e um único detalhe pequeno em dourado fosco (#b0904f). Os elementos ficam concentrados nos cantos e nas bordas da imagem, alguns cortados pela borda. O centro fica vazio e liso, para receber botões por cima. Sem brilho, sem reflexo, sem efeito 3D chamativo, sem degradê forte, sem texto, sem letras, sem números, sem pessoas, sem logotipos.
```

### 4. Fundo de "Apps do dia a dia"

Anexar: `apps/marca/folha-da-marca.png`.
Elementos ligados a: A Gosto, Compra Planejada, Plano Viagem Certa, Carteira, Prancheta e Organizador Pessoal.

```
Use a folha da marca anexada só como referência de estilo e de cores: formas lisas, cantos levemente arredondados, sem brilho e sem efeito 3D. Não copie a folha e não reproduza o símbolo, o nome nem nenhum texto dela.

Crie uma imagem de fundo horizontal, em formato paisagem, para uma página de menu, em estilo sóbrio, minimalista e plano. Fundo marfim claro (#f6f3ee). A imagem traz, de forma discreta, elementos da rotina de casa: uma panela com colher; uma cesta de compras; um alfinete de mapa e uma mala de viagem; um gráfico de pizza com algumas moedas; um halter e uma prancheta de treino; e uma lista de tarefas com itens marcados, feita só de traços, sem letras. Entre eles, blocos quadrados dispostos em grade, como ícones de aplicativo.

Os desenhos são simples e planos, como papel recortado em camadas, com sombra muito suave. A maior parte deles fica em tons de marfim e cinza-claro, quase da cor do fundo. Poucos elementos em verde-escuro (#1f5244) e em grafite (#24272e), e um único detalhe pequeno em dourado fosco (#b0904f). Os elementos ficam concentrados nos cantos e nas bordas da imagem, alguns cortados pela borda. O centro fica vazio e liso, para receber botões por cima. Sem brilho, sem reflexo, sem efeito 3D chamativo, sem degradê forte, sem texto, sem letras, sem números, sem pessoas, sem logotipos.
```

## Simulação da marca aplicada (opcional)

Serve para apresentar a marca, não como arquivo final. Anexe `padroes/marca/png/assinatura-horizontal.png`.

```
Foto realista e sóbria de um cartão de visita e de um caderno de capa lisa sobre uma mesa de madeira clara, com luz natural suave. Aplique a marca da imagem anexada no cartão e na capa do caderno, sem alterar as formas, as cores, as proporções nem as letras da marca. Paleta do ambiente em marfim, grafite e vinho escuro. Sem outros textos e sem outras marcas.
```
