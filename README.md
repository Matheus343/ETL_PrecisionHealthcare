# 🏥 Precision Healthcare — Predição de Reinternações Hospitalares com Machine Learning

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Streamlit](https://img.shields.io/badge/streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Google_Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white)
![Status](https://img.shields.io/badge/STATUS-CONCLUÍDO-green?style=for-the-badge)

---

# 📌 Descrição do Projeto

O **Precision Healthcare** é uma solução de análise preditiva desenvolvida para identificar pacientes com alto risco de reinternação hospitalar em até 30 dias após a alta médica.

O projeto foi desenvolvido como parte do **Projeto Final de Engenharia de Computação da Faculdade Engenheiro Salvador Arena (CEFSA)** e integra conceitos de:

- Engenharia de Dados
- Data Warehouse & OLAP
- Estatística Aplicada
- Machine Learning
- Business Intelligence
- Inteligência Artificial Generativa

A solução utiliza um pipeline completo de dados para transformar informações clínicas em insights estratégicos, permitindo que hospitais atuem preventivamente antes da reinternação ocorrer.

---

# 🎯 Problema de Negócio

Reinternações hospitalares representam:

- Custos elevados para instituições de saúde
- Sobrecarga hospitalar
- Riscos clínicos ao paciente
- Falhas no acompanhamento pós-alta

Segundo os dados analisados:

- **11%** dos pacientes foram reinternados em menos de 30 dias
- O dataset contém mais de **101 mil internações**
- Dados provenientes de **130 hospitais dos EUA**

Nosso objetivo foi prever antecipadamente esses casos e apoiar decisões clínicas através de dashboards e IA.

---

# 👥 Equipe

| Integrante | Responsabilidade |
|---|---|
| **Adriana Monteiro Martani** | Documentação, QA e Validação Estatística |
| **Analuz Marin Ramos** | ETL, Pipeline e Transformação de Dados |
| **Matheus Xavier** | Arquitetura, OLAP e IA Generativa |
| **Yasmin Laisa Maciel** | Machine Learning e Avaliação de Modelos |

🎓 **Orientador:** Prof. Dr. Fábio Henrique Cabrini

---

# 🏗️ Arquitetura da Solução

```text
Dataset UCI
    ↓
Pipeline ETL
    ↓
Star Schema
    ↓
EDA + Estatística
    ↓
Machine Learning
    ↓
Dashboard OLAP
    ↓
Gemini AI Insights
