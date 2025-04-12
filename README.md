---

## 💳 Detecção de Fraudes em Transações Financeiras  

---

### 📌 Descrição do Projeto

Este projeto tem como objetivo identificar transações financeiras fraudulentas utilizando técnicas de análise de dados e machine learning. Através da exploração de dados e modelagem preditiva, buscamos construir um sistema que possa diferenciar operações legítimas de fraudes, ajudando a prevenir perdas financeiras.

---

### 🧠 Problema

Fraudes em transações financeiras representam perdas bilionárias todos os anos. Identificar essas fraudes rapidamente é essencial para proteger os consumidores e instituições financeiras. O desafio está no desequilíbrio dos dados (a maioria das transações são legítimas), exigindo soluções inteligentes que saibam detectar comportamentos anômalos com precisão.

---

### 📦 Utilização

#### Dependências

Para rodar este projeto, é necessário ter as seguintes bibliotecas instaladas no ambiente Python:

- Python 3.x  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Imbalanced-learn (SMOTE)

---

### ⚙️ Instalação

**No Google Colab:**
!pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn

**Localmente:**
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn

---

### ▶️ Executando o Projeto

1. Baixe o dataset: [Credit Card Fraud Detection - Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)  
2. Carregue o dataset no ambiente do Google Colab  
3. Explore e limpe os dados  
4. Crie e avalie os modelos de machine learning  
5. Visualize os resultados através de gráficos e métricas

---

### 📊 Etapas do Projeto

1. **Análise Exploratória de Dados (EDA)**
2. **Seleção de Variáveis Relevantes**
3. **Pré-processamento**
4. **Modelagem**
5. **Conclusão com Insights**

---

### 📈 Resultados

- **Random Forest**  
  - Recall: ~78%  
  - AUC: ~0.93

- **Regressão Logística**  
  - Recall alto, mas baixa precisão

---

### 💡 Insights

- O SMOTE teve papel fundamental no balanceamento
- O Random Forest obteve melhor equilíbrio entre detecção e falsos positivos

---

### 🔄 Próximos Passos

- Testar outros modelos como XGBoost  
- Ajustar o limiar de decisão  
- Criar uma aplicação interativa com Streamlit ou Flask

---

### 🗂️ Estrutura do Projeto

```
├── project_creditcard.ipynb         
├── creditcard.csv                   
├── modelo_random_forest.pkl         
└── README.md                        
```

---

### 👩‍💻 Autores

Thais Aparecida dos Santos Cardoso

---

### 📌 Histórico de Versões

- 0.1 - Primeira versão do projeto

---

### 📜 Licença de Uso

Este projeto é de uso livre e segue a licença MIT.

---

### 📚 Fontes de Inspiração

- Kaggle: [Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)  
- [Documentação do Scikit-learn](https://scikit-learn.org)

---
