# Desafio SeuBoné Análise de dados

<a target="_blank" href="https://colab.research.google.com/github/AldoQueirozTinoco/Desafio-SeuBone/blob/main/Notebook_desafio_seubon%C3%A9.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>

## Descrição

Projeto feito em código python com notebook jupyter e análise gráfica com Power BI para o desafio em análise de dados da SeuBoné.

O desafio é dividido em duas partes:

1. Carregamento e armazenamento dos dados
2. Construção de visualizações a partir dos dados carregados.

Utilizando Python:
- Fiz o download e carreguei os dados em um notebook para análise de forma periódica.
- Realizei uma verificação de qualidade dos dados importados.

Utilizando Power BI criei um dashboard para mostrar as seguintes informações:
- Quais os top 3 produtos mais exportados por estado nos anos de 2020 e 2021;
- Quais os top 3 produtos mais importados por estado nos anos de 2020 e 2021;
- Quais os top 3 produtos exportados em cada mês de 2021 por estado;

Os dados foram retirados da base de dados Comex Stat a respeito do comércio exterior disponibilizadas pelo governo federal
- [Informações sobre layout de dados](https://www.gov.br/mdic/pt-br/assuntos/comercio-exterior/estatisticas/base-de-dados-bruta)

  >Foram utilizados os dados da "Base de dados detalhada por NCM"

  ## Bibliotecas
  - Pandas
  - Numpy

  ## Rodando o projeto
  O projeto pode ser aberto tanto localmente quanto em um notebook jupyter

  ### Para abrir no google colab
  O arquivo Notebook_desafio_seuboné.ipynb permite visualização direta no github, porêm caso necessário
  também pode ser importado para qualquer aplicação que compile o framework jupyter como o google colab. (Link Open in Colab deixado no início)


  Para abrir localmente são necessárias as instalações do Python e pip,
  após a instalação do pip, as bibliotecas devem ser instaladas na root
  
  ``pip install numpy``
  ``pip install pandas``

  Agora o notebook pode ser compilado.
