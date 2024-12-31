# Projeto de Regressão Linear com PySpark 🏡

Este projeto utiliza **PySpark** para realizar uma análise preditiva de preços de imóveis. Desde a manipulação e limpeza de dados até a aplicação de regressão linear, o objetivo é demonstrar como big data e machine learning podem ser usados para resolver problemas reais.

---

## 🔍 Descrição do Projeto

O projeto foca em:

- **Leitura de dados no formato JSON** diretamente do Google Drive.
- **Exploração e limpeza de dados**, incluindo tratamento de valores ausentes e conversões de tipos.
- **Análise de correlações** com visualizações gráficas.
- **Treinamento e avaliação de um modelo de Regressão Linear** para prever preços de imóveis.
- **Cálculo de métricas de desempenho**, como R² e RMSE, para avaliar a eficácia do modelo.

---

## 📂 Estrutura do Projeto

- **`/data`**: Dados de entrada no formato JSON.
- **`notebook`**: Contém o código executado passo a passo no Google Colab.
- **`visualizacoes`**: Gráficos gerados para análise de correlação.

---

## 🚀 Tecnologias Utilizadas

- **PySpark**: Para manipulação e modelagem de grandes volumes de dados.
- **Google Colab**: Ambiente para execução do código.
- **Seaborn e Matplotlib**: Visualização de correlações.
- **Pandas**: Para manipulação adicional de dados.
- **Python**: Linguagem de programação principal.

---

## 🛠️ Como Executar

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/seuusuario/nome-do-repositorio.git


2. **Acesse o Google Colab e abra o notebook fornecido**
3. **Faça upload dos dados ou configure o caminho para o Google Drive.**
4. **Instale as dependências**:
   !pip install pyspark

5. **Execute célula por célula e acompanhe as etapas descritas no notebook**

## 📊 Resultados Obtidos
**Coeficiente de Determinação (R²):**
Dados de treino: 0.665587
Dados de teste: 0.658521

**Erro Médio Quadrático (RMSE):**
Dados de treino: 810348.969532
Dados de teste: 800525.969683


Essas métricas mostram a qualidade do modelo para prever preços com base nos dados fornecidos.








   
