# 📊 Dashboard de Indicadores da Emergência – AGHUse / HGI

## 📌 Visão Geral do Projeto

Este projeto apresenta a construção de um **dashboard analítico completo**, desenvolvido no **Power BI**, utilizando dados extraídos de **relatórios PDF mensais do AGHUse** (Aplicativo de Gestão Hospitalar) referentes à Emergência do **Hospital Geral de Ipiaú – BA (HGI)**. O projeto foi realizado de forma **voluntária** durante minha atuação como implantador do sistema, com o objetivo de apoiar a gestão hospitalar através de dados.

Por questões de sigilo, o dashboard original não pode ser disponibilizado. No entanto, este repositório contém um **protótipo com dados fictícios** e um PDF com **frames reais** do dashboard final.

---

## 🎯 Problema Identificado

Apesar da grande quantidade de informações produzidas diariamente pela emergência, a instituição não possuía uma ferramenta que consolidasse os dados de forma clara e que permitisse análises históricas, visualização de padrões, identificação de gargalos e apoio à tomada de decisão.

Os relatórios do AGHUse eram disponibilizados **apenas em PDF**, o que dificultava análises avançadas e a construção de indicadores.

---

## 🎯 Objetivos do Projeto

* Transformar relatórios PDF em dados utilizáveis.
* Integrar **10 meses** de informações da emergência.
* Criar um dashboard interativo, claro e orientado à decisão.
* Entregar KPIs essenciais sobre fluxo assistencial, gravidade, demanda, diagnósticos e tempo de atendimento.
* Permitir análises de comportamento, picos de demanda e tendência.
* Apoiar direção e coordenação em decisões estratégicas.

---

## 📂 Fontes de Dados

* **Relatórios mensais em PDF** do módulo de emergência do AGHUse.
* Cada PDF contém estruturas tabulares distintas, exigindo padronização manual.
* Não há acesso a SQL, banco ou API: toda a extração foi realizada a partir de PDFs.

---

## 🔧 Processo de Extração e Transformação

1. **Download mensal** dos PDFs diretamente no AGHUse.
2. Conversão dos PDFs para **Excel**.
3. **Tratamento e padronização** das tabelas (campos, tipos, colunas ausentes, fusão de tabelas, datas, horas, padrões textuais).
4. Uso do Power BI para:

   * Clean-up final.
   * Normalização de dados.
   * Criação de relações.
   * Construção de medidas em **DAX**.
5. Construção do dashboard final.

---

## 🧱 Arquitetura do Processo

```
AGHUse (PDF mensal)
        ↓
Conversão PDF → Excel
        ↓
Tratamento e Padronização
        ↓
Importação no Power BI
        ↓
Modelagem • DAX • EDA
        ↓
Dashboard Final
```

---

## 📊 KPIs Principais

### ⏱ Indicadores de Tempo

* Tempo médio Chegada → Acolhimento
* Tempo médio Chegada → Atendimento
* Tempo médio Acolhimento → Atendimento
* Tempo médio de Atendimento
* Tempo médio por hora (24h)
* Tempo médio até a alta por classificação de risco
* Máximo de dias em atendimento por gravidade

### 📈 Indicadores Operacionais

* Total de Entradas
* Total de Atendimentos
* Total de Pacientes
* Total de Retornos
* Total de Altas
* Atendimentos por mês, dia, hora e turno
* Atendimentos por Semana Epidemiológica
* Distribuição por cidades e estados

### 👶 Perfil dos Pacientes

* Distribuição por sexo
* Faixas etárias completas (0 a 80+)
* Análise de atendimento neonatal

### ⚠ Classificação de Risco (Protocolo Manchester)

* Top 5 classificações de risco
* Entradas por cor
* Distribuição por sexo, idade e cidade

### 🏥 Diagnósticos

* Top 5 diagnósticos por atendimento
* Top 15 diagnósticos gerais
* Análises temáticas:

  * Cefaleia
  * Trauma
  * Febre
  * Alterações glicêmicas
  * Ferimentos
  * Ansiedade

### 🔥 Ocorrências e Picos Críticos

* Heatmap Hora × Mês
* Horários de maior demanda
* Identificação de gargalos

---

## 📌 Principais Insights (exemplo com dados fictícios)

* Horários críticos concentrados entre **08h e 14h**.
* Diagnósticos mais frequentes relacionados a **dor**, **gastroenterites**, **cefaleia** e **trauma**.
* Adultos jovens e adultos representam mais da metade dos atendimentos.
* Grande fluxo de pacientes de cidades da região, não apenas de Ipiaú.
* Picos de atendimento semanais e variação mensal relevante.

---

## 🧠 Habilidades Desenvolvidas

* Extração e manipulação de dados não estruturados (PDF)
* EDA no contexto hospitalar
* Power BI (DAX, modelagem, relacionamentos)
* Storytelling com dados
* Construção de KPIs de saúde
* Entendimento de operação hospitalar de emergência

---

## 📁 Arquivos do Repositório

* `projeto-treinamento-hgi-melhorado.pbix` → Modelo fictício
* `hgi-analise.pdf` → Frames do dashboard real (dados anonimizados)
* README.md (este arquivo)

---

## 📎 Contato

**Higgor** – Analista / Cientista de Dados
**Telefone:** 77 998132632
**LinkedIn:** https://www.linkedin.com/in/higgor-sa/
