<h1> 📊 Análise de evasões - TelecomX<h1>
<h2>🔎 Objetivo</h2>
<h3>Investigar a causa de evasões por parte dos clientes com base em dados </h3>
<h2>🚀 Passo a passo do projeto</h2>
<h3>Extração de Dados.</h3>

Dados importados de arquivo .json.

<h3>Transformação</h3>

- Normalização da estrutura em um DataFrame.
- Conversão de colunas numéricas (ex: TotalCharges) para tipo adequado.
- Tratamento de valores nulos e criação da coluna Daily_Charge.
- Mapeamento binário de variáveis textuais (Sim/Não → 1/0).

<h3>Análise Exploratória</h3>

- Visualizações com gráficos de barras, histograma, boxplot e heatmap.
- Análise de rotatividade por tempo de contrato, tipo de serviço, método de pagamento, etc

<h2>🚨 Principasi fatores</h2>

- Clientes recentes (< 6 meses) – Clientes novos apresentam maior risco de cancelar.

- Contratos mensais – Taxa de churn de 42,7%, bem mais alta que contratos de 1 ano (11,1%) e 2 anos (2,9%).

- Daily_Charge elevado – Valores diários altos aumentam a evasão.

- Pagamento via Electronic Check – Forma de pagamento associada a maior cancelamento.

- Baixo uso de serviços – Clientes que não utilizam Internet, Suporte Técnico ou Backup têm mais chance de cancelar.

- Insatisfação com serviços críticos – Problemas percebidos em OnlineSecurity e DeviceProtection.

- Demografia – Jovens/adultos sem parceiros ou dependentes apresentam maior churn. 

- Falta de Internet – Clientes sem serviço de internet têm risco maior de cancelamento.

- Serviços contratados, mas não valorizados – DeviceProtection e TechSupport podem gerar churn devido à percepção de baixo benefício.

- Custos elevados – Tarifas mensais ou diárias altas podem causar percepção negativa de custo-benefício.
