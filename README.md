# 📊 Dashboard de Indicadores da Emergência – HGI / AGHUse

## 📌 Visão Geral

Este projeto apresenta o desenvolvimento de um **dashboard analítico em Power BI** para monitoramento da operação da emergência do Hospital Geral de Ipiaú (HGI), utilizando dados extraídos de relatórios mensais do sistema hospitalar **AGHUse**.

O projeto foi desenvolvido durante minha atuação como implantador do sistema na instituição, com o objetivo de **transformar dados operacionais em informações estratégicas para apoio à gestão hospitalar**.

Por questões de confidencialidade, os dados originais não podem ser disponibilizados. Este repositório contém:

- Um **modelo de dashboard com dados fictícios**
- Um **PDF com frames do dashboard real (anonimizados)**

---

# 🎯 Problema de Negócio

Apesar da grande quantidade de dados gerados diariamente pela emergência hospitalar, a instituição não possuía uma ferramenta que consolidasse essas informações de forma visual e analítica.

Os relatórios do sistema **AGHUse** eram disponibilizados apenas em formato **PDF**, dificultando:

- análises históricas
- identificação de padrões
- monitoramento de indicadores
- tomada de decisão baseada em dados

---

# 🎯 Objetivos do Projeto

O projeto teve como objetivos principais:

- Transformar **relatórios PDF em dados estruturados**
- Consolidar **1 (um) ano (2025) de dados da emergência**
- Criar **indicadores operacionais e assistenciais**
- Construir um **dashboard interativo para gestores**
- Identificar **picos de demanda e gargalos operacionais**

---

# 📂 Fonte dos Dados

Relatórios mensais em PDF extraídos do sistema hospitalar **AGHUse**.

Cada relatório contém diversas tabelas operacionais da emergência, incluindo:

- fluxo de pacientes
- tempos de atendimento
- classificação de risco
- diagnósticos
- perfil demográfico

Não havia acesso a banco de dados ou API, portanto **todo o processo de extração foi realizado a partir dos PDFs**.

---

# 🔧 Pipeline de Dados

O fluxo de tratamento dos dados seguiu as seguintes etapas:

AGHUse (Relatórios PDF mensais)
↓
Conversão PDF → Excel
↓
Tratamento e padronização das tabelas
↓
Importação no Power BI
↓
Modelagem de dados
↓
Criação de medidas DAX
↓
Construção do dashboard analítico


Principais etapas de transformação:

- padronização de colunas
- normalização de dados
- tratamento de datas e horários
- consolidação de múltiplas tabelas
- criação de relacionamentos

---

# 📊 Principais Indicadores (KPIs)

## ⏱ Indicadores de Tempo

- Tempo médio **Chegada → Acolhimento**
- Tempo médio **Chegada → Atendimento**
- Tempo médio **Acolhimento → Atendimento**
- Tempo médio de atendimento
- Tempo médio por hora (24h)
- Tempo médio até alta por classificação de risco

---

## 📈 Indicadores Operacionais

- Total de entradas
- Total de atendimentos
- Total de pacientes
- Total de retornos
- Total de altas
- Atendimentos por mês
- Atendimentos por dia da semana
- Atendimentos por turno
- Atendimentos por semana epidemiológica

---

## 👶 Perfil dos Pacientes

- Distribuição por sexo
- Faixa etária completa (0 a 80+)
- Análise de atendimento neonatal

---

## ⚠ Classificação de Risco (Protocolo Manchester)

- Distribuição por cores de risco
- Top classificações de risco
- Análise por sexo e idade

---

## 🏥 Diagnósticos

- Top 5 diagnósticos por atendimento
- Top 15 diagnósticos gerais
- Análise de diagnósticos por categorias clínicas

---

# 🔥 Análise de Picos de Atendimento

Foi desenvolvido um **heatmap Hora × Mês** para identificar padrões de demanda.

Principais análises:

- horários de maior demanda
- variações mensais
- identificação de possíveis gargalos no fluxo de atendimento

---

# 📊 Exemplos de Insights

Com base na análise dos dados (exemplo com dados fictícios):

- Maior volume de atendimentos entre **08h e 14h**
- Predominância de atendimentos em **adultos jovens e adultos**
- Alta incidência de diagnósticos relacionados a:
  - cefaleia
  - trauma
  - gastroenterites
  - febre
- Fluxo significativo de pacientes provenientes de **cidades da região**, não apenas de Ipiaú

---

# 🧠 Habilidades Demonstradas

Este projeto envolveu o desenvolvimento de competências importantes em análise de dados:

- Extração de dados não estruturados (PDF)
- Limpeza e padronização de dados
- Análise exploratória de dados (EDA)
- Modelagem de dados no Power BI
- Criação de métricas e KPIs com DAX
- Visualização de dados
- Storytelling com dados

---

# 🛠 Tecnologias Utilizadas

- Power BI
- DAX
- Excel
- Data Cleaning
- Análise Exploratória de Dados (EDA)

---

# 📁 Arquivos do Repositório

- projeto-treinamento-hgi-melhorado.pbix → modelo de dashboard com dados fictícios
- hgi-analise.pdf → frames do dashboard real (dados anonimizados)
- README.md → documentação do projeto


---

# 📌 Observação

Os dados originais não podem ser divulgados devido a restrições de confidencialidade institucional. O objetivo deste repositório é demonstrar o **processo analítico, a modelagem e a construção do dashboard**.

---

# 👤 Autor

**Higgor Sampaio Alves**

Graduando em Ciência de Dados  
Jequié – BA

GitHub  
https://github.com/higgor-s-a
