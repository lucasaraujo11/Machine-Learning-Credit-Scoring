
# 🏦 Credit Score com Machine Learning

Este projeto implementa um modelo simples de **credit scoring** usando **Regressão Logística**. O objetivo é prever se um cliente deve ou não receber crédito com base em dados socioeconômicos e financeiros.

A base de dados foi obtida do repositório da Alura e está traduzida para o português.

---

## 🧠 Tecnologias Usadas

- Python
- pandas
- matplotlib
- scikit-learn

---

## ⚙️ Passos do Projeto

1. Carregamento da base de dados
2. Pré-processamento das variáveis
3. Engenharia de variáveis
4. Treinamento do modelo
5. Avaliação por matriz de confusão, relatório de classificação e curva ROC

---

## 📂 Fonte dos Dados

Os dados foram carregados diretamente de:
```
https://raw.githubusercontent.com/alura-cursos/credit_scoring/main/base_dados_traduzida.csv
```

---

## ▶️ Execução

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/nome-do-repo.git
   cd nome-do-repo
   ```
2. Execute o script principal:
jupyter notebook credit_score_model.ipynb

---

## 📌 Observações

- O código é autoexplicativo e modularizado.
- O classificador usado é a **Regressão Logística**, com métricas como Acurácia, F1-Score e AUC.
- A curva ROC e matriz de confusão ajudam na visualização da performance do modelo.

---

## 📈 Resultados

**Modelo: Regressão Logística**
**Métricas avaliadas:**
- Acurácia
- Precision, Recall, F1-score
- Curva ROC com AUC
**Visualizações geradas:**
**Matriz de confusão**
**Curva ROC**

---

## 📁 Estrutura do Projeto
seu-projeto/
├── credit_score_analysis.ipynb  
├── credit_scoring_course.ipynb
├── ML_Credit_Scoring_Certificado.pdf 
├── modelo.ipynb
├── README.md                    
└── dataset/                     
    ├── base_dados_traduzida.csv
    ├── german_credit.csv
    └── german_dataset_dictionary.txt

---

## 📃 Licença

Este projeto está sob a licença **MIT**.

---

## ✍️ Autor

- [Lucas Leite Araujo](https://github.com/lucasaraujo11)