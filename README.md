# 🏥 Dashboard de Análise da Emergência Hospitalar

## 📌 Sobre o Projeto

Este projeto tem como objetivo analisar dados operacionais da emergência do Hospital Geral de Ipiaú (BA), com foco na identificação de padrões, gargalos e oportunidades de melhoria no atendimento.

A análise foi desenvolvida a partir de dados reais, extraídos de relatórios do sistema hospitalar, permitindo uma visão detalhada do fluxo assistencial.

---

## 🎯 Problema de Negócio

A gestão de emergências hospitalares enfrenta desafios como:

* Alto volume de atendimentos
* Longos tempos de espera
* Dificuldade na identificação de gargalos operacionais

Diante disso, surge a necessidade de transformar dados operacionais em informações estratégicas para apoiar a tomada de decisão.

---

## 🧩 Objetivo

* Analisar o fluxo de pacientes na emergência
* Identificar padrões de demanda ao longo do tempo
* Avaliar tempos de atendimento
* Apoiar decisões relacionadas à alocação de recursos

---

## ⚙️ Processo de Dados (ETL)

### 🔹 Extração (Extract)

* Dados obtidos a partir de relatórios em PDF do sistema hospitalar (AGHUse)

### 🔹 Transformação (Transform)

* Limpeza e padronização dos dados
* Tratamento de valores ausentes
* Integração de múltiplos períodos (12 meses - 2025)
* Criação de variáveis analíticas

### 🔹 Carga (Load)

* Modelagem dos dados no Power BI
* Construção de dashboard interativo

---

## 📊 Principais Insights

* ⏱️ O tempo médio de atendimento na emergência ultrapassa **8 horas**, indicando possível sobrecarga operacional
* 📈 Há maior concentração de atendimentos durante o período diurno
* 🟢 A maioria dos atendimentos é classificada como **baixa gravidade (verde e amarelo)**
* 🧠 Os principais motivos de atendimento estão relacionados a **dores e sintomas clínicos gerais**
* 🔁 Alto volume de retornos pode indicar necessidade de melhoria na resolutividade dos atendimentos

---

## 📷 Dashboard

### Visão Geral

![Visão Geral](./images/overview.png)

### Indicadores Principais

![KPIs](./images/kpis.png)

### Análise de Tempo de Atendimento

![Tempo](./images/tempo_atendimento.png)

### Análise de Demanda

![Demanda](./images/demanda.png)

---

## 🛠️ Ferramentas Utilizadas

* Python
* Power BI
* Excel

---

## 💡 Impacto do Projeto

Este projeto permite:

* Identificar gargalos no fluxo de atendimento
* Apoiar a tomada de decisão na gestão hospitalar
* Melhorar a alocação de recursos
* Contribuir para redução de tempo de espera

---

## 🚀 Possíveis Melhorias Futuras

* Automatização do pipeline de dados (ETL)
* Integração com banco de dados
* Atualização em tempo real
* Criação de alertas para horários críticos

---

## 👨‍💻 Autor

**Higgor Sampaio Alves**
🔗 [LinkedIn](https://linkedin.com/in/higgor-sa)
🔗 [GitHub](https://github.com/higgor-s-a)
