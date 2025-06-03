from pathlib import Path

readme_content = """
# 📊 Dashboard Financeiro – Análise de Receita e Fluxo de Caixa

Este projeto apresenta um **dashboard financeiro interativo** desenvolvido com foco em análise de **receitas, despesas e fluxo de caixa**, permitindo uma visão gerencial e estratégica da performance financeira ao longo do tempo.

---

## ✨ Funcionalidades

- **Análise de Receita por Conta**  
  Visualização detalhada da origem da receita, destacando categorias como:
  - Prestação de Serviços
  - Vendas de Mercadorias
  - Empréstimos e Financiamentos
  - Produtos e Serviços Técnicos

- **KPIs Financeiros Principais**
  - Receita Total: `R$ 27,677K`
  - Despesa Total: `R$ 31,188K`
  - Margem de Contribuição: `R$ 6,601K`
  - % de Variação Anual da Receita: `+87.81%`
  - Receita do Ano Anterior (mReceitaLY): `R$ 14,737K`

- **Evolução Mensal da Receita**
  Gráfico comparativo entre receita atual (Receita) e receita do ano anterior (ReceitaLY), por mês e trimestre.

- **Análise de Despesas Fixas e Variáveis**
  Visualização percentual por tipo de despesa ao longo dos meses.

- **Fluxo de Caixa**
  Tabela dinâmica com entradas, saídas, saldo inicial/final e resultado do período mês a mês.

---

## 🧩 Filtros Interativos

- **Ano**: 2017, 2018, 2019  
- **Mês**: Filtro mensal dinâmico  
- **Tipo de Conta**: Operacional e Não Operacional  
- **Tipo de Data**: Emissão, Liquidação, Vencimento  
- **Cliente / Fornecedor**: Filtros específicos para análise granular

---

## 🛠 Tecnologias Utilizadas

- Power BI (Visualizações, DAX, Filtros e Interações)
- Modelagem de dados em Power Query
- Transformações e cálculos com foco gerencial

---

## 📌 Observações

- O dashboard permite **mudança entre visualização visual e tabular**, tornando a análise mais flexível.
- Todos os KPIs e gráficos são **dinâmicos e interdependentes**, respeitando os filtros selecionados.
- Ferramenta ideal para **análise de lucratividade, planejamento financeiro e controle de custos**.

---

## 📷 Screenshots

| Receita vs LY | Fluxo de Caixa |
|:-------------:|:--------------:|
| ![Receita](./caminho/para/0a8a071a.png) | ![Fluxo de Caixa](./caminho/para/838034ff.png) |

---

## 📞 Contato

Desenvolvido por [José Henrique Hasenfratz Brandão](https://www.linkedin.com/in/jhhasenfratz/)  
Especialista em FinOps | BI | FP&A | Power BI
"""

# Caminho do arquivo de saída
readme_path = Path("/mnt/data/README_Dashboard_Financeiro.md")
readme_path.write_text(readme_content, encoding="utf-8")

readme_path

