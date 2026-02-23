# 📊 Análise Exploratória de Dados Logísticos

## 🎯 Objetivo

Realizar uma análise exploratória da base de operações logísticas, com o objetivo de compreender padrões operacionais, variabilidade das entregas e identificar possíveis fatores associados à performance e à ocorrência de reclamações.

---

## Base de Dados

Base contendo 1.000 viagens com informações sobre:

- Produto transportado
- Tipo de caminhão
- Distância percorrida
- Número de entregas
- Número de paradas do motorista
- Duração da viagem
- Indicador de reclamação

---

## 🔎 Metodologia

A análise foi conduzida utilizando Excel, com aplicação de:

- Estatísticas descritivas
- Análise de dispersão e correlação
- Boxplots e análise de distribuição
- Segmentação por categorias
- Information Value (IV)
- Coeficiente de determinação (R²)

---

## 📈 Principais Achados

### 🔹 Perfil Operacional
- A maioria das viagens ocorre em 1 dia.
- 75% das viagens realizam até 6 entregas.
- Produtos A e B concentram a maior parte do volume.
- Caminhões de tanque médio são os mais utilizados.

### 🔹 Relações Operacionais
- Forte correlação (0,73) entre número de entregas e distância percorrida.
- Alta variabilidade na distância e no número de paradas.

### 🔹 Fatores Associados a Reclamações
- O tipo de produto apresentou forte poder discriminatório (IV elevado).
- Distância percorrida e número de paradas apresentaram baixo poder explicativo.

---

## 🧠 Conclusões

A análise indica que variáveis estruturais relacionadas ao tipo de produto possuem maior impacto sobre a ocorrência de reclamações do que variáveis puramente operacionais.
Os resultados sugerem oportunidades de aprofundamento em análises segmentadas por categoria de produto e revisão de processos específicos.

---

## 🛠 Ferramentas Utilizadas

- Excel
- Tabelas Dinâmicas
- Fórmulas Avançadas
- Análise Estatística Descritiva

---

## 📌 Possíveis Evoluções

- Modelagem preditiva com regressão logística
- Automatização com Power Query
- Dashboard interativo em Power BI
- Implementação em Python (Pandas)
