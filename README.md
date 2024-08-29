# Projeto de Portfólio
**Em andamento.** <br>
Em breve, novidades.

# Sobre o projeto

A indústria de jogos digitais entrega grande volume de produções todos os anos e, como qualquer outro setor, necessita que seus produtos **desempenhem bem no mercado**.

Portanto, **determinar quais nichos de jogos e clientes** trarão tal resultado é essencial para a continuidade dos projetos de uma empresa desse ramo.

Com esse contexto em mente, durante este estudo serão analisadas as vendas de jogos digitais com objetivo de encontrar padrões que auxiliem nessa tomada de decisão tão impactante.

Esse estudo terá como base a metodologia proposta no **CRISP-DM** e será organizado em duas partes:

**Parte 1**: Foco na construção da **EDA - Análise Exploratória dos Dados**, buscando aprofundar o conhecimento sobre o contexto e fortalecer  a solução do problema em destaque.

**Parte 2**: Centrada na construção de um **modelo de machine learning** que auxiliará a alcançar o **objetivo** proposto.

# Sobre o conjunto de dados

O conjunto de dados escolhido para conduzir essa investigação pode ser encontrado na plataforma Kaggle: [**Video Game Sales**](https://www.kaggle.com/datasets/gregorut/videogamesales/data)

Nesse dataset há as seguintes variáveis:

- Rank - Classificação geral das vendas
- Name - Nome do jogo
- Platform - Platforma de lançamento do jogo (PC,PS4, etc.)
- Year - Ano de lançamento do jogo
- Genre - Gênero do jogo
- Publisher - Empresa responsável pela publicação do jogo
- NA_Sales - Vendas na América do Norte (em milhões)
- EU_Sales - Vendas na Europa (em milhões)
- JP_Sales - Vendas no Japão (em milhões)
- Other_Sales - Vendas em outras regiões (em milhões)
- Global_Sales - Total mundial de vendas

# Objetivo e questões norteadoras

Ao longo desse trabalho, será construído um **modelo de recomendação de lançamento de jogos por região** baseado nos padrões de vendas observados nos dados.

### **Objetivo**

**Recomendação de gêneros populares por região** 
Quais gêneros de jogos devem ser lançados em uma região específica para maximizar as vendas?

Para tal, serão respondidas questões mais objetivas que auxiliarão a destrinchar o tema elencado.

As perguntas estão agrupadas para facilitar a organização geral do estudo. Abaixo, está a relação de tópicos abordados:

**Impacto do gênero nas vendas**

- Quais gêneros de jogos têm o maior sucesso em termos de vendas globais?
- Qual região (América do Norte, Europa, Japão, Outras) é mais forte em termos de vendas para diferentes gêneros?
- Existem padrões regionais nas preferências de gêneros de jogos?

**Tendências temporais de lançamento e venda**

- Como as vendas de jogos mudaram ao longo do tempo?
- Existe uma correlação entre o ano de lançamento e o sucesso de vendas em diferentes regiões?

**Impacto da publisher nas vendas**

- Quais publishers tendem a ter jogos com maiores vendas globais e por região?
- Quais publishers têm mais lançamentos por gênero?
- Existe diferença significativa nas vendas entre publishers para jogos do mesmo gênero?

# Andamento do projeto

- **Parte 1 completa** e disponível no documento “Parte 01 - EDA.ipynb” no repositório do GitHub.
- Parte 2 está estruturada e com documentação realizada até a organização para a modelagem e já disponível no repositório do GitHub.
    
    **Próximos passos**
    
    - Construção dos modelos propostos.
    - Avaliação dos modelos.
    - Ajustes e reaplicação dos modelos.
    - Reavaliação e conclusões da modelagem.
    - Documentação devida de todos os passos citados.
