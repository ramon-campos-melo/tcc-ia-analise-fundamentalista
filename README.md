# O Uso da Inteligência Artificial na Análise Fundamentalista para Tomada de Decisão no Mercado de Ações

## Descrição

Este repositório contém o trabalho de conclusão de curso (TCC) apresentado ao [Centro Universitário Carioca (UniCarioca)](https://unicarioca.edu.br/) como requisito a obtenção do grau de Bacharel em Ciência da Computação, intitulado "O Uso da Inteligência Artificial na Análise Fundamentalista para Tomada de Decisão no Mercado de Ações". O projeto explora a aplicação de técnicas de Inteligência Artificial (IA) na análise fundamentalista de empresas listadas na bolsa de valores brasileira, com o objetivo de otimizar a tomada de decisão de investimentos. Embora o modelo de IA desenvolvido não tenha mostrado rentabilidade positiva no período testado, os resultados oferecem insights valiosos sobre os desafios e as limitações da utilização de IA em estratégias de investimento.

## Objetivo

O principal objetivo do trabalho é apresentar e avaliar um modelo de IA capaz de analisar dados financeiros de empresas, utilizando a análise fundamentalista como base, e gerar recomendações de investimentos no mercado de ações. O estudo incluiu uma revisão bibliográfica detalhada sobre IA, mercado de ações e análise fundamentalista, além de uma avaliação qualitativa e quantitativa dos resultados do modelo desenvolvido.

## Tecnologias Utilizadas

* Google Colaboratory: Ambiente de desenvolvimento para execução do código e análise de dados.
* Python: Linguagem de programação principal para a construção do modelo de IA. As bibliotecas utilizadas incluem: 
  * `os`, `zipfile`: Manipulação e extração de arquivos.
  * `pandas`, `pandas_datareader`, `yfinance`: Coleta e processamento de dados financeiros.
  * `matplotlib.pyplot`, `seaborn`, `plotly.express`: Visualização de dados.
  * `sklearn`: Implementação de modelos de machine learning (classificação).

## Estrutura do Repositório

A estrutura do repositório está organizada da seguinte maneira:

* [`balancos_zip`](./balancos_zip): Contém 100 arquivos ZIP com balanços financeiros das empresas
* [`balancos`](./balancos): Contém 100 arquivos .xls extraídos dos arquivos ZIP
* [`TCC_IA_Analise_Fundamentalista.pdf`](./TCC_IA_Analise_Fundamentalista.pdf): Trabalho escrito em formato PDF
* [`tcc_ia_analise_fundamentalista.ipynb`](tcc_ia_analise_fundamentalista.ipynb): Código do projeto
* [`licenca`](./LICENSE): Arquivo de licença

## Créditos e Autoria

* Alunos: Fernando Passos Mello e [Ramon Ramalho Campos](https://www.linkedin.com/in/ramon-campos-melo)
* Orientadora: [Prof.ª Daisy Cristine Albuquerque da Silva](https://www.linkedin.com/in/daisyalbuquerque)
* Coordenador: [Prof. Sérgio Assunção Monteiro](https://www.linkedin.com/in/sergio-assun%C3%A7%C3%A3o-monteiro-b781897b)

## Status do Projeto

Este projeto está finalizado. Embora não tenha gerado resultados de rentabilidade positiva, os insights obtidos fornecem uma base para futuras melhorias e explorações no campo da Inteligência Artificial aplicada aos investimentos. Este projeto pode ser expandido e aprimorado em uma futura pesquisa ou projeto.

## Considerações Finais

A implementação de Inteligência Artificial no mercado de ações é um campo promissor, mas ainda repleto de desafios. Os resultados deste estudo indicam que, embora o modelo desenvolvido não tenha sido rentável, ele oferece informações valiosas sobre como a IA pode ser utilizada para apoiar a tomada de decisão no mercado financeiro. Portanto, futuros aprimoramentos no modelo podem levar a resultados mais promissores.

## Licença

Este projeto está licenciado sob a licença Creative Commons Attribution 4.0 International (CC BY 4.0), permitindo o uso, distribuição e modificação do conteúdo, desde que a autoria seja atribuída corretamente.
