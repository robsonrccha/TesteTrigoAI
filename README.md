# 📦 Análise de Dados - E-commerce Brasileiro (Olist) 🇧🇷

Este projeto foi desenvolvido como parte do Teste Técnico do Programa Trainee da **triggo.ai** na trilha de **Engenharia de Dados e DataOps**. Utilizando o dataset público da Olist, realizamos uma série de análises exploratórias, predições e visualizações com foco em gerar **insights estratégicos para o negócio**.

---

## 🚀 Como Executar o Projeto

### 1. Requisitos

- Python 3.8+
- Google Colab (recomendado) ou Jupyter Notebook
- Conexão com Google Drive (caso use Colab)
- Bibliotecas:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `plotly`
  - `scikit-learn`

### 2. Etapas de Execução

1. **Clone o repositório** ou acesse os notebooks via Colab
2. Baixe o dataset do Kaggle: [Brazilian E-commerce Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
3. Salve os arquivos CSV em uma pasta do seu Google Drive
4. Execute os notebooks na seguinte ordem:

   📁 notebooks/
├── Tarefa_1_Preparacao_Dados_Colab
├── Tarefa_2_Analise_Exploratoria
├── Tarefa_3_Solucao_Problemas_Negocio
└── Tarefa_4_Visualizacoes_Dashboards


5. Siga as instruções em cada notebook para configurar o caminho correto e rodar as análises

---

## 🔎 Principais Resultados

### 📊 Tarefa 2 – Análise Exploratória

- **Picos de vendas** em novembro e dezembro, indicando **sazonalidade de fim de ano**
- **Tempo médio de entrega** varia bastante, com muitos pedidos acima de 10 dias
- **Frete mais caro** está correlacionado com maior distância (proxy via CEP)
- **Categorias campeãs de faturamento**: cama, mesa e banho; relógios; celulares
- **Estados com maior ticket médio**: RJ, SP, AM

### 🧠 Tarefa 3 – Solução de Problemas

- **Apenas ~16% dos clientes** são recorrentes
- **Modelo de Random Forest** previu atrasos com base em tempo de aprovação e envio
- **Segmentação de clientes** revelou 3 grupos com diferentes perfis de compra
- **Tempo de entrega está diretamente relacionado à nota da avaliação**

### 📈 Tarefa 4 – Dashboards

- **Dashboard interativo** com filtro por categoria e estado
- **Mapa de calor** mostra concentração de vendas em SP e RJ
- **Painel de vendedores** destaca os melhores em volume, avaliação e agilidade

---

## 🛠 Tecnologias

- Python, Pandas, NumPy, Matplotlib, Seaborn
- Plotly Express para gráficos interativos
- Scikit-Learn para modelagem preditiva
- KMeans para clustering







