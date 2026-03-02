# Exploração de Dados: Preços de Combustíveis no Brasil (2025)

Este repositório contém o projeto de análise exploratória de dados desenvolvido para a disciplina de [Nome da sua Disciplina]. O objetivo foi aplicar técnicas estatísticas e de visualização utilizando Python para extrair insights de um dataset público real.

## 📊 Dataset Escolhido
* **Nome:** Série Histórica de Preços de Combustíveis e de GLP (1º Semestre de 2025).
* **Órgão:** Agência Nacional do Petróleo, Gás Natural e Biocombustíveis (ANP).
* **Fonte:** [Portal Brasileiro de Dados Abertos](http://dados.gov.br)
* **Descrição:** O conjunto de dados apresenta os preços praticados por revendedores de combustíveis automotivos em todo o território nacional.

## 🛠️ Ferramentas Utilizadas
* **Ambiente:** Google Colab
* **Linguagem:** Python 3.x
* **Bibliotecas:** * `Pandas`: Manipulação e limpeza de dados.
    * `Matplotlib` e `Seaborn`: Geração de gráficos estatísticos.
    * `Numpy`: Cálculos matemáticos.

## 📈 Análises Realizadas
O projeto seguiu as seguintes etapas:
1.  **Limpeza de Dados:** Conversão de tipos de dados (strings para floats) e tratamento de separadores decimais padrão brasileiro (vírgula para ponto).
2.  **Estatística Descritiva:** Cálculo de média, mediana, moda, desvio padrão, variância e quartis (Q1, Q3 e IQR).
3.  **Visualização:** * **Boxplot:** Identificação de dispersão e *outliers* (preços fora do padrão).
    * **Gráfico de Dispersão:** Análise da variação de preços ao longo do tempo (janeiro a julho de 2025).

## 💡 Principais Insights
* Os preços de combustíveis como o GLP apresentaram estabilidade durante o período analisado, concentrando-se em faixas horizontais claras.
* O Boxplot revelou a presença de **outliers**, indicando pontos de venda com preços significativamente superiores à média nacional, possivelmente devido a custos logísticos regionais.

---
**Desenvolvido por:** Felipe Lopes (Gigi)  
**Status do Projeto:** Concluído ✅