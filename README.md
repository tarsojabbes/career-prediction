# Career Prediction :chart_with_upwards_trend:

## Projeto de Visualização Interativa de Dados
Este projeto tem como objetivo criar uma visualização interativa utilizando a biblioteca Apache ECharts para explorar as tendências de carreira dos estudantes de Ciência da Computação. A visualização permite ao público filtrar e interagir com os dados de forma intuitiva, oferecendo insights sobre como habilidades em linguagens de programação e desempenho acadêmico influenciam as escolhas de carreira.

## Tecnologias Utilizadas
- **JavaScript**: Lógica da visualização interativa.
- **Apache ECharts**: Biblioteca utilizada para a criação dos gráficos.
- **HTML/CSS**: Estrutura e estilo da página.

## Descrição do Projeto
Este projeto conta duas histórias baseadas no dataset fornecido `cs_students.csv`:

### 1. Correlação entre GPA e áreas de escolha de carreira
- [x] **Objetivo**: Mostrar como diferentes níveis de GPA influenciam as escolhas de carreira.
- [x] **Visualização**: Um gráfico de barras empilhadas no qual o eixo X apresenta valores de GPA e as barras empilhadas representam as diferentes áreas de estudo.
- [x] **Elementos interativos**:
  - Filtro por gênero (todos, homens, mulheres).
  - Zoom para focar em uma faixa específica de valores de GPA.
  - Tooltip que exibe a quantidade de pessoas em cada área ao passar o mouse.

### 2. Diferença de escolhas de carreira entre homens e mulheres
- [x] **Objetivo**: Comparar a distribuição de escolhas de carreira de estudantes com base no gênero.
- [x] **Visualização**: Utiliza o gráfico de barras empilhadas do GPA, permitindo filtrar a visualização por gênero para explorar as diferenças.
- [x] **Elementos interativos**:
  - Filtro por gênero.
  - Zoom para reduzir o intervalo de GPA exibido.
  - Tooltip mostrando a quantidade de pessoas em cada área.

## Como Interagir com a Visualização
Basta abrir o arquivo HTML `Lab6-GrupoE-VisualizacaoFinal.html` em qualquer navegador moderno para visualizar e interagir com os dados.
