# Coffee-Break-Co

# Problema de negócio
    
  A **Coffee Break Co.** é uma rede de cafeterias que opera em grandes centros urbanos, com foco em atendimento rápido e qualidade do café. A empresa compete em um mercado saturado, onde a retenção de clientes e a otimização da operação são vitais. O principal desafio da gestão é garantir que a **eficiência operacional** e as **decisões de *mix* de produtos** estejam alinhadas com a **lucratividade**.
    
   O Problema de Negócio (Desafio de Gestão)
    "Como podemos otimizar a alocação de pessoal e aumentar o Ticket Médio da Coffee Break Co., explorando a sazonalidade de vendas por Dia da Semana e identificando o *mix* de produtos mais eficaz para *upsell*?"
    

### Dado da empresa

Análise Descritiva

Passo 1 Coluna:

- Data
- Time
- Turno
- Hora do dia
- Tipo de pagamento
- Preço
- Nome do café
- Nome do Turno

Passo 2: Combinação das Dimensões

- Quantidade de Vendas por Ano/Mês
- Quantidade de Vendas por Nome do café
- Quantidade de Vendas por Tipo de pagamento
- Quantidade de Vendas por Turno
- Preço médio por Turno
- Preço médio por Tipo de café
- Premissas do negócio
    - **Varejo de Alta Frequência:** O negócio é caracterizado por um **alto volume de transações e baixo Ticket Médio**
    - **Foco no Consumo Rápido e Local:** O desempenho é altamente sensível à **sazonalidade diária e semanal**
    
    Visão do negócio: visão Geral
    
## Estratégia da solução
    
  O painel estratégico foi desenvolvido utilizando as métricas que refletem a visão principal  do modelo de negócio da empresa:
    
  1. Visão Geral
    
  A visão é representada pelo seguinte conjunto de métricas.
    
  1. Visão Geral
      1. Faturamento ano 2024
      2. Faturamento ano 2025
      3. Faturamento total
      4. Taxa de crescimento 2024-2025        
      5. Faturamento por ano/mês
      6. Análise de pareto 
      7. Análise de setor por turno 
        
## Top 3 insights de dados
  1. Variação de Faturamento Mensal (Tendências Sazonais)
  - **Picos de Vendas:** Os meses de **dezembro de 2024** ($1.608.077) e **março de 2025** ($1.321.548) apresentaram os maiores faturamentos.
- **Baixa de Vendas:** **Abril de 2024** ($59.052) e **maio de 2024** ($816.642) foram os meses com menor faturamento. O pico de dezembro, próximo ao final do ano, e o de março, no início, podem indicar tendências de consumo associadas a feriados/festividades e início de ano fiscal, respectivamente.
2.  Faturamento por Tipo de Café (Análise de Pareto)
    
     A curva de Pareto mostra a concentração do faturamento:
    
    - **Os 3 Principais Produtos (62% do Faturamento):** Os tipos de café **Latte**, **Americano com Leite** e **Cappuccino** representam, juntos, **62%** do faturamento total.
        - **Latte:** O produto mais vendido, com **$2.509.897** (24% do total).
        - **Americano com Leite:** Segundo, com **$2.319.970**.
        - **Cappuccino:** Terceiro, com **$1.608.077**.
    - **Concentração (80/20):** Os **5 principais produtos** (**Latte, Americano with Milk, Cappuccino, Americano e Hot Chocolate**) são responsáveis por **84%** do faturamento. Isso confirma que a maior parte da receita depende de um pequeno número de produtos.
    - **Produtos de Menor Contribuição:** **Cortado** ($634.446) e **Espresso** ($240.948) são os que menos contribuem.
3. Faturamento por Turno (Distribuição Horária)
    
    O faturamento está distribuído de forma relativamente uniforme ao longo do dia, com uma leve preferência pela noite:
    
    - **Night (Noite):** **35%** do faturamento.
    - **Morning (Manhã):** **33%** do faturamento.
    - **Afternoon (Tarde):** **32%** do faturamento.
- O produto final
    
    Dashboard Online, na ferramenta power Bi online e disponível para acesso em qualquer dispositivo conectado à internet.
    
    O painel pode ser acessado através desse link[:https://app.powerbi.com/view?r=eyJrIjoiZmZlNTcxYmEtOWMzMS00YTUwLWEyYTYtYmNlZDI1ZGVmYWNiIiwidCI6ImZiY2ExYWE5LTAxMDEtNDRlNC1iZmU1LWEyODRjNzA0YjIyMCJ9&pageName=d9d429c736f89c578732](https://app.powerbi.com/view?r=eyJrIjoiODVhZjJmZGUtZTkzNS00NTkzLTg5NDktMzVhODYwYWM2MjUzIiwidCI6ImZiY2ExYWE5LTAxMDEtNDRlNC1iZmU1LWEyODRjNzA0YjIyMCJ9&pageName=abea1fa31c8965278c00)
    
# Conclusão
    
  Pontos Chave da Conclusão:
    
  1. **Concentração de Receita (Pareto):** A saúde financeira da empresa está altamente concentrada. Os **três principais tipos de café (Latte, Americano com Leite e Cappuccino) respondem por 62% do faturamento total**. Isso indica uma necessidade de foco em garantir a qualidade e disponibilidade desses itens, mas também um risco por excesso de dependência.
    
  2. **Alerta Crítico de Crescimento:** Um dos *insight* mais relevantes é a **alta de 1591% na Taxa de Crescimento entre 2024-Mar e 2025-Mar,** mostra uma alta tendência de crescimento.
    
  3. **Oportunidade de Otimização Sazonal e de Turno:** As vendas aparentam ser fortemente sazonais, para uma melhor análise sazonal o ano de 2025 tem que está completo . Além disso, a distribuição de faturamento é equilibrada entre os turnos (noite ligeiramente à frente), sugerindo que as estratégias de marketing e promoções devem ser personalizadas para manter o desempenho em cada período do dia.
