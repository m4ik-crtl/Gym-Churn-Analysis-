# Gym Churn Analysis 🏋️‍♂️📉

Este projeto faz parte do **bootcamp de análise de dados** e tem como objetivo estudar a **retenção e cancelamento de clientes (churn)** em uma rede de academias nos EUA.

## 🎯 Objetivo
Analisar os dados de clientes e prever o risco de churn, de forma a apoiar o time de marketing e retenção na definição de estratégias.

## 📊 Etapas do Projeto
1. **Preparação dos Dados**  
   - Carregamento e tratamento do dataset `gym_churn_us.csv`  
   - Verificação de nulos e duplicados  
   - Criação de variáveis auxiliares  

2. **Análise Exploratória (EDA)**  
   - Estatísticas descritivas  
   - Distribuição de idade, frequência e tempo de contrato  
   - Comparação de churners vs não churners  

3. **Modelagem Preditiva**  
   - Divisão em treino e teste  
   - Regressão logística  
   - Random Forest  
   - Avaliação com **ROC-AUC, precisão e recall**  

4. **Clusterização de Clientes**  
   - K-Means para segmentação de perfis  
   - Identificação de grupos mais propensos ao churn  

5. **Conclusões Parciais por Capítulo**  
   - Insights ao longo da análise sobre perfil e comportamento dos clientes  

6. **Conclusão e Recomendações**  
   - Identificação de variáveis mais relevantes para retenção  
   - Sugestões práticas para reduzir churn  

## ✅ Conclusões Principais
- Clientes com **contratos mensais** apresentam maior risco de churn.  
- Frequência de visitas é um dos fatores mais fortes para prever retenção.  
- Segmentos distintos de clientes foram identificados com base em idade, visitas e tipo de contrato.  
- Modelos preditivos atingiram boa performance (**ROC-AUC > 0.85**).  

## 🚀 Recomendações
- Incentivar planos de **longo prazo (6-12 meses)**.  
- Criar programas de engajamento para aumentar a frequência semanal.  
- Desenvolver ações específicas para segmentos mais vulneráveis ao churn.  

---

## 📂 Estrutura do Repositório
- `notebook.ipynb` → notebook principal com toda a análise  
- `gym_churn_us.csv` → base de dados usada no projeto  
- `README.md` → documentação do projeto  

---

👨‍💻 Desenvolvido por [Maikon Silva](https://www.linkedin.com/in/maikon-silva-457b98181/)  
