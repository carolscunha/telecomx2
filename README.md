## 📞 Análise de Evasão de Clientes - TelecomX

Este projeto realiza uma análise exploratória e preditiva sobre a evasão (churn) de clientes de uma operadora fictícia de telecomunicações, com o objetivo de identificar os fatores que mais influenciam a saída dos clientes e desenvolver estratégias de retenção.

Além da análise exploratória, foram criados e comparados diferentes modelos de Machine Learning para prever a evasão.


---

### 🔍 Objetivos da Análises

-Identificar os principais fatores que levam à evasão.

-Construir e avaliar modelos preditivos.

-Comparar o desempenho de diferentes algoritmos.

-Apoiar decisões estratégicas para redução da evasão. 

---

## 📈 Visualizações Criadas

📊 Taxa Geral de Evasão
Gráfico mostrando a proporção de clientes que saíram versus os que permaneceram.

📂 Distribuição por Variáveis Categóricas
Visualizações para variáveis como tipo de contrato, serviço de internet e método de pagamento.

📈 Correlação entre Variáveis Numéricas
Mapa de calor para identificar relações entre as variáveis e a evasão.

🏆 Comparação de Desempenho dos Modelos
Gráfico comparando métricas como Acurácia, Precisão, Recall e F1-score.

📌 Importância das Variáveis
Gráficos mostrando quais variáveis mais influenciaram a previsão da evasão.


---

### 🧪 Tecnologias Utilizadas

1- Python

2- Pandas — análise e tratamento de dados

3- Matplotlib & Seaborn — visualização de dados

4- Scikit-learn — criação e avaliação de modelos de Machine Learning

---

### 📊 Principais Insights

1- Clientes com contrato mensal têm maior probabilidade de evasão.

2- Valores altos de cobrança mensal estão associados a maior churn.

3- Uso de serviço de internet por fibra ótica tem correlação positiva com evasão.

4- Clientes com menor tempo de permanência tendem a cancelar mais.

---

### 🤖 Modelos Criados
-Regressão Logística (com normalização dos dados)

-Random Forest (sem necessidade de normalização)

### 📌 Métricas Avaliadas:

Acurácia

Precisão

Recall

F1-score

Matriz de confusão

---

### ✅ Conclusão

O modelo Random Forest apresentou melhor desempenho geral, especialmente em Recall, sendo mais eficiente para identificar clientes que irão sair.
Principais fatores que influenciam a evasão:

Tipo de contrato (mensal)

Alto valor de cobrança mensal

Menor tempo de permanência

Método de pagamento (cartão ou boleto eletrônico)

Sugestões de retenção:

Incentivar contratos anuais com descontos.

Oferecer pacotes personalizados para clientes com alto valor mensal.

Criar programas de fidelidade para novos clientes.

---

### 🚀 Como Executar

1. Acesse o notebook no Google Colab ou Jupyter Notebook.  
2. Execute o notebook por seção.

---

### 📌 Autora

<img src="https://github.com/user-attachments/assets/ee1f5e42-ce53-4afe-93d2-ad5a9d2ebdcc" alt="Foto de Perfil" width="150" height="150"/>

Desenvolvido por **[Caroline Cunha]**  

Você pode me encontrar em:  
- [LinkedIn](https://www.linkedin.com/in/carolinecunha92)

Projeto baseado no *Challenge de Data Science* da [Alura](https://www.alura.com.br/)
