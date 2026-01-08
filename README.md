# Impacto da Maternidade e Economia do Cuidado no Brasil

Este projeto analisa como a maternidade e a carga de trabalho doméstico invisível impactam a participação das mulheres no mercado de trabalho brasileiro, com base em dados do IBGE.

## 📊 Principais Insights do Dashboard
- [cite_start]**O Abismo da Maternidade:** Enquanto **87% dos pais** mantêm seus empregos, apenas **54% das mães** conseguem o mesmo[cite: 11].
- [cite_start]**Sobrecarga de Cuidado:** As mulheres dedicam quase o dobro do tempo dos homens a afazeres domésticos (cerca de **20h vs 10h** semanais)[cite: 42].
- [cite_start]**Desigualdade Estrutural:** Mulheres pretas e pardas enfrentam as maiores taxas de desocupação e informalidade, recebendo em média apenas **64% do rendimento** de mulheres brancas[cite: 67, 138].
- [cite_start]**Impacto da Pandemia:** Em 2020, o fechamento de creches causou uma queda imediata na ocupação das mães[cite: 19].

## 🛠️ Desafios Técnicos e Soluções
Este foi meu primeiro projeto no Power BI e envolveu um processo intenso de dados:
1. **ETL (Extração e Limpeza):** Consolidei **28 planilhas do IBGE** que estavam em formatos distintos.
2. **Categorização:** Limpei e categorizei os dados para garantir que a análise regional (Norte, Nordeste, etc.) e racial estivesse correta.
3. **DAX e IA:** Utilizei Inteligência Artificial como parceira de pensamento para estruturar medidas DAX complexas, como taxas de desocupação e cálculos de rendimento proporcional.

## 📂 Estrutura do Repositório
- `/dados`: Planilhas tratadas.
- `/projeto`: Arquivo .PBIX do Power BI.
- `/relatorio`: PDF final com os visuais.
