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

<h2>🚀 Recomendações para Redução de evasões</h2>

1. <h3>Fortalecer a Experiência nos Primeiros Meses (0–6 meses)</h3>

- Criar um programa de onboarding com suporte dedicado.

- Enviar check-ins periódicos (ex: quinzenais) para verificar a satisfação inicial.

- Disponibilizar tutoriais rápidos e um FAQ interativo para orientar novos clientes.

2. <h3>Incentivar Contratos de Longo Prazo</h3>

- Conceder 15% de desconto em renovações anuais.

- Oferecer 3 meses gratuitos em contratos bienais.

- Enfatizar a economia ao longo do tempo para reduzir a adesão a contratos mensais.

3. <h3>Aumentar o Valor Percebido dos Serviços</h3>

- Criar pacotes como o bundle “Segurança Total” (OnlineSecurity + TechSupport + Backup) com desconto de 20%.

- Realizar campanhas de educação do cliente, mostrando os benefícios dos serviços adicionais.

4. <h3>Melhorar a Experiência de Pagamento</h3>

- Auditar o processo de Electronic Check e resolver problemas de usabilidade.

- Incentivar a migração para débito automático ou cartão com 5% de desconto.

- Comunicar de forma clara a segurança e praticidade desses métodos.

5. <h3>**Campanhas de Retenção Segmentadas**</h3>

- Focar em jovens/adultos sem dependentes, novos clientes e usuários de fatura digital.

- Enviar ofertas personalizadas antes do término do contrato.

- Oferecer planos flexíveis para clientes em risco.

6. <h3>Melhorar a Qualidade de Serviços Críticos</h3>

- Realizar pesquisas de satisfação e auditorias em OnlineSecurity, DeviceProtection e TechSupport.

- Reforçar a comunicação de valor desses serviços.

7. <h3>Equilibrar Custo e Benefício</h3>

- Avaliar clientes com altos MonthlyCharge/DailyCharge para identificar insatisfação.

- Criar planos personalizados que equilibrem custo e valor entregue.

- Demonstrar o ROI (retorno sobre o investimento) com dados claros.

- Falta de Internet – Clientes sem serviço de internet têm risco maior de cancelamento.

- Serviços contratados, mas não valorizados – DeviceProtection e TechSupport podem gerar churn devido à percepção de baixo benefício.

- Custos elevados – Tarifas mensais ou diárias altas podem causar percepção negativa de custo-benefício.
