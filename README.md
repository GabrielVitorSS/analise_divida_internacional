# analise_divida_internacional
Analisando estatísticas da dívida internacional

![2B3C2F29-EF86-4EC9-B3BA-2AC79D144D2E](https://github.com/user-attachments/assets/61c73d0f-2cec-49d0-8b45-3b7a888a672c)
Humans not only take debts to manage necessities. A country may also take debt to manage its economy. For example, infrastructure spending is one costly ingredient required for a country's citizens to lead comfortable lives. The World Bank is the organization that provides debt to countries.

In this project, you are going to analyze international debt data collected by The World Bank. The dataset contains information about the amount of debt (in USD) owed by developing countries across several categories. You are going to find the answers to the following questions:

What is the number of distinct countries present in the database?
What country has the highest amount of debt?
What country has the lowest amount of repayments?
Below is a description of the table you will be working with:
## `international_debt` table

| Column | Definition | Data Type |
|-|-|-|
|country_name|Name of the country|`varchar`|
|country_code|Code representing the country|`varchar`|
|indicator_name|Description of the debt indicator|`varchar`|
|indicator_code|Code representing the debt indicator|`varchar`|
|debt|Value of the debt indicator for the given country (in current US dollars)|`float`|

## Perguntas e respostas
Aqui estão 3 perguntas e seus respectivos resultados que devem ser respondidas utilizando a tabela acima.
### Questão 1
Qual é o número de países distintos presentes no banco de dados? A saída deve ser uma única linha e coluna com o alias total_distinct_countries. Salve a consulta como num_distinct_countries.
![65D99943-1BFC-45BD-950A-D7F88196D84F_4_5005_c](https://github.com/user-attachments/assets/99cb08a3-139d-473c-b43e-b4f1f8e45131)

### Questão 2
Qual país tem a maior dívida? Sua saída deve conter duas colunas: country_name e total_debt, além de uma linha. Salve a consulta como highest_debt_country.
![26D791AF-53A6-4DFD-8E2E-F253CB9C87E6_4_5005_c](https://github.com/user-attachments/assets/8408e5af-f629-4f7a-b7a7-1702e0c55b78)

### Questão 3
Qual país possui o menor valor de reembolsos (indicado pelo código de indicador ‘DT.AMT.DLXF.CD’)? A tabela de saída deve conter três colunas: nome_do_país, nome_do_indicador e menor_reembolso, com apenas uma linha, salva na consulta lowest_principal_repayment.
![FF1FDFCD-0406-448E-819F-E59245F9A3DF_4_5005_c](https://github.com/user-attachments/assets/1164decf-27ad-42fb-b301-6e70ee989db7)
