# Análise de Desempenho - Alura Store

## 📝 Descrição do Projeto

Este projeto realiza uma análise comparativa do desempenho de quatro unidades da Alura Store. O objetivo principal é identificar a loja com o desempenho mais fraco, fornecendo subsídios para uma decisão estratégica de negócios (por exemplo, a venda de uma das unidades). A análise se baseia em dados reais de vendas e avaliações dos clientes.

## 🎯 Objetivo

Identificar qual das quatro lojas da Alura Store apresenta o desempenho mais fraco, com base em métricas de faturamento, vendas por categoria, avaliação dos clientes, produtos mais/menos vendidos e frete médio, para auxiliar na tomada de decisão sobre qual unidade seria mais indicada para uma eventual venda.

## 📊 Dataset

Os dados utilizados neste projeto são provenientes do desafio de Data Science da Alura (Challenge 1 - Data Science), consistindo em arquivos CSV separados para cada uma das quatro lojas, contendo informações sobre produtos, categorias, preços, fretes, datas de compra, vendedores, locais de compra, avaliações e pagamentos.

Os datasets são carregados diretamente das seguintes URLs:
* Loja 1: `https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_1.csv`
* Loja 2: `https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_2.csv`
* Loja 3: `https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_3.csv`
* Loja 4: `https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_4.csv`

## 🛠️ Metodologia e Análises Realizadas

A análise foi conduzida utilizando Python com as bibliotecas Pandas para manipulação de dados, e Matplotlib e Seaborn para visualização. Os seguintes critérios foram avaliados:

1.  **Faturamento Total:** Comparação da receita total gerada por cada loja.
2.  **Vendas por Categoria de Produtos:** Identificação das categorias com maior e menor volume de vendas em cada loja e no geral.
3.  **Média de Avaliação dos Clientes:** Análise da satisfação dos clientes por loja.
4.  **Produtos Mais e Menos Vendidos:** Identificação dos produtos específicos com maior e menor saída em cada unidade.
5.  **Frete Médio por Loja:** Comparação do custo médio de frete para os clientes de cada loja.
6.  **Visualizações Comparativas:** Criação de gráficos para facilitar a interpretação e comparação dos dados entre as lojas.

## 📈 Principais Descobertas e Visualizações

O projeto inclui diversas visualizações para ilustrar as descobertas, como:

* Gráfico de barras do faturamento total por loja.
* Gráfico de barras comparativo de vendas por categoria entre as lojas.
* Gráfico de pizza da distribuição geral de categorias de produtos.
* Gráfico de barras da média de avaliação por loja.
* Gráfico de barras dos produtos mais e menos vendidos por loja.
* Gráfico de barras do frete médio por loja.
* Gráfico de barras da avaliação média por faixa de preço.


## 💡 Conclusão e Recomendação

Com base na análise detalhada dos dados, **a Loja 4 foi identificada como a unidade com o desempenho mais fraco** e, portanto, a mais indicada para uma eventual venda.

**Principais justificativas para esta recomendação:**
* Apresentou o menor faturamento total entre as quatro lojas.
* Demonstrou desempenho inferior em categorias de produtos importantes, como "Eletrodomésticos".
* Sua média de avaliação dos clientes ficou abaixo das lojas com melhor desempenho (Lojas 2 e 3).
* Embora o frete médio seja competitivo, este fator isolado não compensa as demais deficiências observadas.

## 💻 Tecnologias Utilizadas

* Python 3
* Pandas
* Matplotlib
* Seaborn
* Jupyter Notebook (ou Google Colab)

## 🚀 Como Executar o Projeto

1.  Clone este repositório:
    ```bash
    git clone [URL_DO_SEU_REPOSITORIO_NO_GITHUB]
    ```
2.  Navegue até o diretório do projeto:
    ```bash
    cd [NOME_DO_SEU_PROJETO]
    ```
3.  Certifique-se de ter as bibliotecas Python necessárias instaladas. Você pode instalá-las usando pip:
    ```bash
    pip install pandas matplotlib seaborn jupyterlab
    ```
4.  Abra o arquivo Jupyter Notebook `challenge_alura_store.ipynb` (ou o nome que você deu ao seu notebook) em um ambiente Jupyter (Jupyter Lab, Jupyter Notebook, Google Colab, VS Code com extensão Python, etc.).
5.  Execute as células do notebook sequencialmente para reproduzir a análise e visualizar os resultados.

## 📂 Estrutura do Projeto

* `challenge_alura_store.ipynb`: Notebook principal contendo todo o código de análise e visualização.
* `README.md`: Este arquivo.


---

*Este README foi gerado com base no projeto de análise da Alura Store. Sinta-se à vontade para adaptá-lo conforme necessário.*
