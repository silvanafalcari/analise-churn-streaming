Análise de Churn — Streaming de Assinatura



Análise exploratória de uma base de clientes de streaming para entender

os fatores associados ao cancelamento (churn) e em que momento da vida

do cliente ele acontece.



\## O problema

Uma empresa de streaming por assinatura quer reduzir o churn, mas não sabe

quem cancela, por quê, nem quando. Este projeto explora a base de clientes

para transformar esses dados em hipóteses acionáveis.



\## Principais descobertas

\- O churn se concentra entre o \*\*2º e o 5º mês\*\* de assinatura — depois

disso, o risco cai bastante.

\- Clientes com \*\*NPS baixo\*\* cancelam muito mais (NPS médio 4,1 entre quem

saiu, contra 7,4 entre quem ficou).

\- A \*\*retenção piorou nas safras mais recentes\*\*, um sinal de alerta sobre

a qualidade da aquisição ao longo do tempo.

\- O plano \*\*Básico\*\* tem a maior taxa de cancelamento.



\## Ferramentas e método

\- \*\*Python\*\*: pandas, matplotlib, seaborn

\- Limpeza e tratamento de dados (escalas, categorias, valores ausentes)

\- Análise univariada e bivariada

\- Frameworks de negócio: cohort, RFM adaptado, Pareto e funil de conversão



\## Como explorar

O notebook completo está em \[`notebooks/analise\_churn.ipynb`](notebooks/analise\_churn.ipynb).



Os dados usados são um conjunto sintético criado para fins didáticos.



\## Autora

Silvana Falcari Morais — \[LinkedIn](https://linkedin.com/in/silvana-falcari-morais-66783a3)

