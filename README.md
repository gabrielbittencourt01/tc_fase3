# 📌 Predição de Diabetes com Streamlit

Este é um aplicativo desenvolvido com **Streamlit** para prever a probabilidade de um usuário ter diabetes com base em algumas informações de saúde e hábitos de vida.

## 🚀 Como Rodar o Projeto

### 1️⃣ **Rodando Localmente**

#### ✅ **Pré-requisitos**
- Python 3 instalado
- Bibliotecas necessárias: `streamlit`, `joblib`, `numpy`

#### 🔹 **Passos para rodar**
1. Clone este repositório:
   ```sh
   git clone https://github.com/SEU_USUARIO/meu-app-diabetes.git
   cd meu-app-diabetes
   ```
2. Instale as dependências:
   ```sh
   pip install -r requirements.txt
   ```
3. Execute o aplicativo:
   ```sh
   streamlit run app.py
   ```
4. O app abrirá no navegador automaticamente.

---

### 2️⃣ **Acessando Online**

O aplicativo pode ser acessado diretamente pelo link:
👉 **[App Online](https://modeloprevisaodiabetestcfase3.streamlit.app/)**

---

## 🏗️ Como Funciona o App

1. O usuário insere dados como **pressão alta, colesterol, IMC, idade, tabagismo**, entre outros.
2. O modelo carregado (`best_model_optimized.pkl`) faz a previsão baseada nos dados inseridos.
3. O resultado é mostrado na tela, indicando a **probabilidade de diabetes**.

---

## 🤖 Modelo Utilizado

O modelo utilizado foi treinado utilizando **Machine Learning** para prever a presença de diabetes com base em um conjunto de características clínicas e comportamentais. 

### 📌 **Processo de Treinamento**
1. Os dados foram carregados e pré-processados.
2. Foram testados diferentes algoritmos de Machine Learning.
3. O modelo vencedor foi salvo como `best_model_optimized.pkl`.
4. O modelo final é carregado no Streamlit para realizar previsões em tempo real.

---

## 📑 Documentação do Notebook

O notebook (`modelo.ipynb`) contém:
- Análise exploratória dos dados.
- Pré-processamento e limpeza dos dados.
- Treinamento e avaliação dos modelos de Machine Learning.
- Comparação entre diferentes algoritmos para escolher o melhor modelo.
- Salvamento do modelo final para uso no aplicativo Streamlit.

Caso queira entender em detalhes como o modelo foi criado, basta abrir o notebook no Jupyter Notebook ou no Google Colab.

---

## 🛠️ Tecnologias Utilizadas
- **Python 3**
- **Streamlit** (Interface Web)
- **Joblib** (Carregamento do modelo)
- **NumPy** (Manipulação de dados)
- **Scikit-Learn** (Treinamento do modelo)

Se precisar de ajuda ou melhorias, sinta-se à vontade para contribuir! 🚀

