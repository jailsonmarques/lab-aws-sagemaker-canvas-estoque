# Desenvolvimento do Modelo de Previsão de Estoque no SageMaker Canvas

## Passo 1: Seleção do Dataset
Para começar, naveguei até a pasta de datasets do repositório. Lá, encontrei diversos datasets disponíveis para uso. Escolhi um dataset que continha o histórico de vendas de um produto específico ao longo de um ano, com informações como data da venda, quantidade vendida e preço médio. Após selecionar o dataset, fiz o upload dele no SageMaker Canvas.

## Passo 2: Construção e Treinamento

### Importação do Dataset
No SageMaker Canvas, importei o dataset que havia selecionado.

### Configuração das Variáveis
Configurei as variáveis de entrada e saída. As variáveis de entrada incluíram data da venda e preço médio, enquanto a variável de saída foi a quantidade vendida.

### Treinamento do Modelo
Iniciei o treinamento do modelo utilizando um algoritmo de regressão linear, adequado para prever valores numéricos como a quantidade de estoque necessária.

## Passo 3: Análise

### Avaliação de Performance
Após o treinamento, avaliei as métricas de desempenho do modelo, como RMSE (Root Mean Square Error) e MAE (Mean Absolute Error), para verificar a precisão das previsões.

### Identificação de Características Importantes
Examinei as principais características que influenciaram as previsões, identificando padrões como sazonalidade nas vendas e o impacto de promoções.

### Ajustes e Retreinamento
Realizei ajustes nos hiperparâmetros do modelo e explorei outros algoritmos para tentar melhorar o desempenho. Após cada ajuste, re-treinei o modelo para obter melhores resultados.

## Passo 4: Previsão

### Previsão de Estoque
Utilizei o modelo treinado para fazer previsões de estoque para o próximo mês, baseando-me nos dados históricos.

### Análise das Previsões
Exportei os resultados das previsões e analisei a precisão comparando com os dados reais.

## Documentação e Conclusões
Documentei todo o processo de desenvolvimento do modelo, incluindo a configuração, os resultados de desempenho e os insights obtidos das previsões de estoque. Concluí o projeto com recomendações para melhorias futuras e lições aprendidas ao longo do desenvolvimento.

---

Este processo detalhado mostra como utilizei o SageMaker Canvas para criar um modelo de previsão de estoque, focando na análise dos dados e iterações para melhorar a precisão das previsões.
