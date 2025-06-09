# 📈 Simulador de Investimentos em Fundos Imobiliários (FII)

![header](https://github.com/devcaiada/excel-investment-simulator/blob/main/assets/header.png?raw=true)

## 🧠 Objetivo do Projeto

Este projeto foi desenvolvido como parte do desafio da DIO com foco na aplicação prática do Microsoft Excel para Análise de Dados Financeiros. O objetivo central é criar uma **ferramenta de simulação de investimentos em fundos imobiliários (FIIs)** que permita ao usuário explorar cenários com base em parâmetros como:

- Valor mensal investido
- Prazo de investimento
- Rentabilidade média estimada
- Acúmulo de dividendos
- Patrimônio total estimado

---

## 📊 Por que Excel é Essencial para a Análise de Dados?

O **Microsoft Excel** é uma das ferramentas mais poderosas e amplamente utilizadas no mundo para análise de dados. Mesmo com o avanço de ferramentas como Python, R ou Power BI, o Excel continua sendo:

- **Rápido e acessível** para simulações financeiras e dashboards.
- **Versátil** para aplicar fórmulas financeiras, gráficos e cenários.
- **Visual e intuitivo**, facilitando a compreensão de dados complexos.

Dominar Excel é um **pré-requisito fundamental para qualquer profissional de dados ou finanças** que deseje atuar com investimentos, planejamento financeiro ou BI.

---

## 📒 Descrição das Abas do Excel

### 📌 Aba: `APP`

Esta é a **interface principal** do simulador. O usuário pode inserir:

- Valor do aporte mensal (ex: R$ 1.000)
- Taxa média de rentabilidade mensal estimada (ex: 0,8% a.m.)
- Número de meses de investimento (ex: 120 meses = 10 anos)

💡 A aba realiza cálculos automáticos como:
- Total aportado (aporte mensal x meses)
- Patrimônio acumulado com base em juros compostos
- Dividendos mensais estimados com base nos fundos escolhidos
- Gráficos de evolução do investimento ao longo do tempo

### 📌 Aba: `Fundos`

Contém dados sobre diferentes **fundos imobiliários**, tais como:

- Nome do fundo
- Rentabilidade média
- Tipo (logístico, shoppings, papel, etc.)
- Dividend yield estimado

Essa aba serve de **base de dados** para alimentar a aba `APP` com informações realistas de mercado.

---

## 📐 Fórmulas Aplicadas

Entre os principais cálculos e fórmulas aplicadas na planilha, destacam-se:

- **Juros Compostos**:
`FV = P * ((1 + i) ^ n - 1) / i`

Onde:
- `FV` = valor futuro acumulado
- `P` = valor do aporte mensal
- `i` = taxa de rendimento mensal
- `n` = número de períodos


- **Dividendos Mensais Estimados**:
`Dividendos = Patrimônio * Dividend Yield`


- **Gráficos dinâmicos** com base nas entradas do usuário

---

## 📸 Exemplos Visuais

### Simulação preenchida

![simulator](https://github.com/devcaiada/excel-investment-simulator/blob/main/assets/simulator.png?raw=true)

### Gráficos de evolução

![chart](https://github.com/devcaiada/excel-investment-simulator/blob/main/assets/chart.png?raw=true)


### Tabela de dividendos projetados

![table](https://github.com/devcaiada/excel-investment-simulator/blob/main/assets/table.png?raw=true)

---

## 🚀 Como Usar

1. Abra o arquivo `Simulador_investimentos_fii.xlsx` em `doc`
2. Vá até a aba `APP`
3. Insira os seguintes dados:
 - Valor do investimento mensal
 - Taxa de rendimento mensal (%)
 - Tempo em meses
4. Observe os resultados calculados automaticamente:
 - Total investido
 - Patrimônio acumulado
 - Dividendos estimados

---

## 🏁 Conclusão

Este projeto consolida os conhecimentos sobre:

- Cálculos financeiros
- Automação de planilhas
- Simulação de cenários de investimento
- Documentação técnica
- Uso profissional do Excel como ferramenta de análise

Além disso, demonstra como a combinação entre Excel e pensamento analítico pode entregar valor real para investidores e empresas do setor financeiro.

---

## 🛠 Tecnologias Utilizadas

- Microsoft Excel 365
- Funções financeiras
- Gráficos e tabelas dinâmicas
- Documentação em Markdown
- Git e GitHub para versionamento e compartilhamento

---

## 📬 Contato

Caso queira discutir este projeto ou tenha sugestões:

- Nome: *Caio Arruda*
- LinkedIn: *[Caio Arruda](https://www.linkedin.com/in/devcaiada/)*
- GitHub: [devcaiada](https://github.com/devcaiada)

---

