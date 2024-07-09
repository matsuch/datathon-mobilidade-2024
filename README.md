# Datathon de Mobilidade Urbana 2024

### Sumario

1. [Sobre o projeto](#brief)
2. [Requisitos](#requirements)
3. [Descrição dos arquivos](#files)
4. [Resultado](#results)

## Sobre o projeto <a name="brief"></a>

Desafio 1: Correlação entre empreendimentos em mobilidade urbana e indicadores de mortos e feridos no trânsito: uma análise com base nos dados da MCID/SEMOB e do atlas da violência

O projeto tem como objetivo analisar os empreendimentos em mobilidade urbana da carteira de empreendimentos da MCID/SEMOB e sua correlação no território com os indicadores de mortos e feridos no trânsito mantidos pelo Atlas da Violência, considerando o tipo de programa do empreendimento.

## Requisitos <a name="requirements"></a>

O código deve ser executado sem problemas usando Python versões 3 com as seguintes bibliotecas: 
  - Visualização de dados: matplotlib, seaborn, plotly, wordcloud
  - Manipulação e Análise de Dados: pandas, numpy, collections
  - Widgets para Jupyter Notebook: ipywidgets
  - Processamento de Linguagem Natural (NLP): nltk, unidecode, spacy, gensim
  - Machine Learning: sklearn

## Descrição dos arquivos <a name="files"></a>

- **Dados**
  - codigo_python.ipynb - *Código python do jupyter utilizado na análise*
  - df_empreendimentos.csv - *tabela com todos os empreendimentos a serem analisados*
  - df_acidentes.csv - *tabela com os acidentes de todos as cidades ano a ano*
  - df_municipios.csv - *tabela com informações dos municípios*
  - df_populacao.csv -  *tabela com as informações populacionais dos municipios*

## Resultados <a name="results"></a>

Ao término da análise, algumas hipóteses e possíveis causas para o desempenho observado na investigação da relação entre os empreendimentos de mobilidade urbana e as taxas de mortalidade no trânsito foram identificadas:

### Base de Dados
- **Ausência de Informações Relevantes:** A ausência de informações relevantes, o preenchimento errado ou insuficiente pode ter prejudicado a compreensão da relação entre os empreendimentos e as taxas de mortalidade no trânsito.
- **Outras obras não listadas:** Ainda que a base de dados dos empreendimentos estivesse robusta, outras obras podem ter sido realizadas nos municípios analisados por fontes de recursos próprios ou por meio de outros programas não relacionados na base de dados atual. A dificuldade no rastreio de tais possíveis obras pode ter comprometido a identificação das ações de trânsito que contribuíram para reduções nas taxas de mortalidade em algumas cidades que apresentaram bons índices neste quesito.
- **Variáveis Não Capturadas:** É possível que outros fatores relevantes não estejam sendo considerados nos dados, como condições meteorológicas, características demográficas, ou políticas de educação no trânsito.

### Complexidade da Relação
- **Fatores interconectados:** A relação entre as características dos empreendimentos de mobilidade urbana e as taxas de mortalidade no trânsito é complexa, envolvendo uma série de fatores interconectados que não foram completamente capturados pelos modelos utilizados. Exemplos incluem ações de educação no trânsito e o fator comportamental dos usuários no sistema viário.

Em resumo, embora esta análise tenha fornecido percepções relevantes, é importante reconhecer as limitações inerentes aos dados e aos modelos utilizados. Futuras pesquisas devem abordar essas questões para avançar na compreensão da relação entre os empreendimentos de mobilidade urbana e a segurança no trânsito, contribuindo para a formulação de políticas mais eficazes e intervenções mais direcionadas.

## Recomendações para futuros avanços

- **Aprimoramento da captação e manutenção da base de dados:** Garantir uma base mais sólida, envolvendo a colaboração com órgãos governamentais de todas as esferas.
- **Expansão do Escopo de Variáveis:** Adicionar outras variáveis de forma a expandir o escopo analisado, como condições meteorológicas, características demográficas, obras de outros empreendimentos/programas e implementação de políticas de educação de trânsito.
- **Reavaliação dos Modelos:** Com melhorias implantadas na manutenção dos bancos de dados, realizar novamente os modelos aqui propostos, permitindo uma nova análise dos resultados em busca de uma validação estatística.

Desta forma, espera-se que, com as melhorias na base de dados e a inclusão de novas variáveis, seja possível obter uma compreensão mais precisa e abrangente da relação entre empreendimentos de mobilidade urbana e segurança no trânsito.
