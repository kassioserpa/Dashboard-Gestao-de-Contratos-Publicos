# 📊 Gestão de Contratos - Dashboard de Inteligência Administrativa

![Status](https://img.shields.io/badge/Status-Concluído-success)
![Role](https://img.shields.io/badge/Role-BI_Engineer-blue)
![Domain](https://img.shields.io/badge/Domain-Public_Administration-lightgrey)

> **Visualização analítica e acompanhamento orçamentário de contratos públicos, focado em transparência, controle de prazos e conformidade com a legislação de licitações.**

---

## 🎯 O Desafio de Negócio

A gestão de contratos na administração pública exige rigor absoluto no controle orçamentário e no cumprimento de prazos. O acompanhamento manual de vigências, notas de empenho e pagamentos frequentemente resulta em ineficiências operacionais, riscos de atraso de pagamento a fornecedores e potenciais quebras de conformidade com a Nova Lei de Licitações e Contratos (Lei nº 14.133/21).

O objetivo deste projeto foi desenvolver uma solução de Business Intelligence automatizada e centralizada para monitorar a saúde financeira e o ciclo de vida dos contratos governamentais.

## 💡 A Solução (Dashboard)

Desenvolvi um painel interativo que permite aos gestores e fiscais de contrato uma visão 360º de cada fornecedor. O dashboard consolida dados dispersos em uma interface limpa e focada em tomada de decisão rápida.

![Dashboard de Gestão de Contratos](./caminho/para/sua/imagem.jpg)

### 📈 Principais Métricas e KPIs (Key Performance Indicators)

O dashboard foi estruturado em três pilares analíticos:

**1. Filtros e Navegação (Slicers)**
* **Empresas:** Listagem dinâmica de fornecedores ativos (ex: Aerotech, Big Chaves, etc.), permitindo o drill-down imediato para a realidade de cada contrato.

**2. Dados Contratuais (Ciclo de Vida & Compliance)**
* **Identificação:** Rastreamento do Nº do Contrato e Nº do Processo Administrativo.
* **Vigência:** Monitoramento preciso das datas de Início e Término, fundamental para renovações tempestivas.
* **Saúde de Pagamento:** Rastreamento do "Último Mês Pago", "Data do Pagamento" e um contador crítico de **"Dias Sem Pagar"**, auxiliando na prevenção de juros, multas ou interrupção de serviços terceirizados.

**3. Orçamento e Execução Financeira**
* **Nota de Empenho:** Rastreamento da dotação orçamentária que garante o recurso.
* **Execução:** Comparativo direto entre "Total Empenhado" e "Valor Pago".
* **Saldo e Disponibilidade:** Cálculo dinâmico do Saldo do Empenho e um gráfico de rosca evidenciando a % de Disponibilidade orçamentária restante, alertando para a necessidade de reforço de empenho antes do esgotamento.

---

## 🛠️ Arquitetura e Tecnologias Aplicadas

* **Visualização de Dados:** Interface desenhada com foco em UX/UI, utilizando princípios de *Data Storytelling* para reduzir a carga cognitiva do usuário.
* **Modelagem de Dados:** Estruturação em *Star Schema* (Fato e Dimensões) para otimizar o tempo de resposta das consultas.
* **DAX (Data Analysis Expressions):** Criação de medidas complexas de inteligência de tempo e regras de negócio específicas da administração pública (ex: cálculo de dias úteis em atraso, percentual de consumo de empenho).
* **Domínio de Negócio:** Aplicação de conceitos intrínsecos à gestão pública (Empenho, Liquidação, Pagamento, Vigência Contratual e alinhamento com a Lei 14.133/21).

---

## 🚀 Impacto Gerado

* **Redução de Risco de Compliance:** Minimização de perdas de prazo para aditivos contratuais.
* **Eficiência Operacional:** Eliminação de horas gastas em conciliação de planilhas de controle paralelas.
* **Transparência:** Facilitação das auditorias e prestação de contas aos órgãos de controle.

---

## 👨‍💻 Autor

**Kássio Serpa** *Data Analyst / BI Engineer* [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kassioserpa/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/kassioserpa)
