# 📊 Dashboard de Analytics: Gatito Petshop

Este projeto consiste no desenvolvimento de um dashboard estratégico e operacional no Power BI para o **Gatito Petshop**, automatizando a análise de dados brutos de clientes para apoiar a tomada de decisões de negócio no setor de varejo e serviços pet.

---

## 🛠️ Ferramentas Utilizadas
* **Power BI Desktop:** Modelagem de dados, criação de métricas e design do relatório.
* **Power Query (ETL):** Limpeza, transformação e tratamento de dados nulos/omissos.
* **Linguagem DAX:** Criação de medidas para análises comparativas de faturamento.

---

## 📐 O Desafio e o Tratamento de Dados (ETL)
A base de dados original conta com um volume de **5.404 registros de clientes**. Durante a etapa de tratamento no Power Query, identificou-se uma inconsistência de **0,04% de dados omissos (em branco)** na segmentação por gênero dos tutores.

Para garantir a integridade visual e analítica do projeto, foi aplicada uma regra de filtragem na camada visual (Filtros Básicos), permitindo focar o faturamento estritamente nas categorias ativas de mercado, mantendo a precisão matemática dos gráficos de pizza e distribuição.

---

## 📈 Principais Insights de Negócio
A partir da análise dos dados consolidados do petshop, destacam-se os seguintes pontos estratégicos:
1. **Predominância Feminina:** O público feminino representa a maior fatia do faturamento do petshop (**54,76%** contra 45,20% do público masculino). Campanhas de marketing e ações sazonais de estética/produtos devem priorizar a comunicação com este perfil.
2. **Fidelização Familiar:** Há uma alta ocorrência de clientes casados com pets ativos, sugerindo uma excelente oportunidade para lançar pacotes de assinatura mensal de serviços recorrentes (como banho e tosa) ou clubes de benefícios para rações.
3. **Geolocalização:** Alta densidade de clientes concentrada na região de Itaquera, o que direciona de forma precisa a criação de anúncios locais (tráfego pago) e parcerias na região.

---

## 📁 Estrutura do Repositório
* `Dashboard_Gatito_Petshop.pbix`: Arquivo original do Power BI para consulta técnica de fórmulas e relacionamentos.
* `Dashboard_Gatito_Petshop.pdf`: Versão estática em PDF do dashboard para visualização rápida.
* `dados.zip`: Arquivo compactado contendo as bases de dados utilizadas no projeto.

---
*Projeto desenvolvido por Derick Leal para fins de portfólio profissional de análise de dados.*
