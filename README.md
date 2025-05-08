# Desafio Alura Store

## Objetivo:
O objetivo do projeto é fornecer insights para o cliente Sr. João decidir sobre o rumo do seu grupo de Lojas Alura.

Tecnologia usada: Python, Google Colab, Google Chrome.

## *Considerações Iniciais:*

I - O cliente enviou uma massa de dados em formato .CSV, representando um período de vendas do seu grupo de lojas.

II - O período contido nos dados indica que os mesmos foram selecionados por algum tipo de amostragem. Não foi informada a metodologia para a seleção.

III - Após, foram analisadas as métricas solicitadas pelo cliente, e foram incluídas métricas extras para ampliar a análise.

      A) Faturamento;

      B) Vendas por Categoria;

      C) Média de Avaliação por Loja (Taxa de Eficiência);

      D) Produtos Mais e Menos Vendidos;

      E) Frete Médio Por Loja;

      F) Outros Indicadores Operacionais: Vendas por Tipo de Pagamento.

IV - Criados Gráficos para melhorar a visualização dos resultados.



## *Ressalvas:*

Provavelmente como fruto da metodologia da amostragem dos dados, todos os indicadores analisados apresentaram resultados bastante similares,
até com certa linearidade, sem grandes desvios da média geral do grupo.

Pela amplitude do período dos dados - 01/2020 a 12/2022, o item *D - Produtos Mais e Menos Vendidos*, apresentou variações maiores, mas que
não chegam a constituir outliers, e também podem estar sujeitas a várias atividades sazonais.

A venda por cartão de crédito compõe mais de 70%, e o custo deste tipo de venda (taxas e tarifas) é bem expressivo.

Venda por Boleto Bancário representa 20% do faturamento, e também um potencial proporcional de inadimplência.

Frete: necessita de estudo mais aprofundado, e pode ter desempenho melhorado.

## Gráficos:

![Grafico_03_Pizza_TP_Recebe](https://github.com/user-attachments/assets/a5bc1125-6bbb-4228-8899-b06c257f9cf5)

![Grafico_04_Barra_TxEfic](https://github.com/user-attachments/assets/473f2f5e-8149-4eff-b0c1-8fd3863943ab)

![Grafico_02_Pizza_Frete](https://github.com/user-attachments/assets/1c9d8992-499a-4751-a254-495ea3cbacf2)


## **Conclusão** ##

PROJETO: Com base nos dados apresentados, e pela período da amostragem ser muito amplo, não é possível afirmar que o Sr. João deva vender 
uma das lojas para investir em um novo negócio, ou fazer outro tipo de investimento.

PESSOAL: Avancei um pouquinho no conhecimento em Data Science pelas dificuldades encontradas no projeto, mas tenho ciência de que as
dificuldades foram apenas pela falta de domínio das ferramentas de análise de dados. Com tempo e prática, esses atropelos iniciais não 
se repetirão, e darão lugar para outros novos aprendizados.


