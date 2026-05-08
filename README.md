# 🏥 Análise Hospitalar com Python e Pandas

Projeto de análise de dados hospitalares com foco em indicadores operacionais, financeiros e estratégicos utilizando Python, Pandas e visualização de dados.

📌 Objetivo do Projeto

O objetivo deste projeto é analisar dados de um hospital para identificar:

padrões de atendimento;
especialidades com maior demanda;
taxas de cancelamento e no-show;
desempenho operacional;
sazonalidade de receita;
oportunidades de melhoria na gestão hospitalar.
🛠️ Tecnologias Utilizadas
Python
Pandas
Matplotlib
Jupyter Notebook
📂 Bases de Dados Utilizadas
| Tabela       | Descrição                       |
| ------------ | ------------------------------- |
| patients.csv     | Informações dos pacientes       |
| doctors.csv      | Dados dos médicos               |
| appointments.csv | Agendamentos e consultas        |
| treatments.csv   | Tratamentos realizados          |
| billing.csv      | Dados financeiros e faturamento |


O projeto utiliza múltiplas tabelas relacionadas:

Tabela	Descrição
patients	Informações dos pacientes
doctors	Dados dos médicos
appointments	Agendamentos e consultas
treatments	Tratamentos realizados
billing	Dados financeiros e faturamento
🔄 Tratamento e Integração dos Dados
📊 Análises Realizadas
💰 Receita por Mês

Análise de sazonalidade da receita hospitalar ao longo do tempo.

Objetivos:
identificar meses de maior e menor faturamento;
entender padrões sazonais;
apoiar planejamento operacional.
👨‍⚕️ Top Médicos com Mais Atendimentos

Ranking dos médicos com maior volume de consultas.

Objetivos:
identificar profissionais mais demandados;
analisar distribuição de atendimentos;
apoiar gestão de carga horária.
🩺 Tratamentos Mais Realizados

Análise dos tratamentos com maior frequência.

Objetivos:
entender principais demandas médicas;
identificar serviços mais utilizados;
auxiliar planejamento de recursos.
❌ Taxa de Cancelamento e No-show

Análise do status das consultas por tipo de atendimento.

Objetivos:
identificar áreas com maior ausência de pacientes;
reduzir desperdício operacional;
melhorar eficiência hospitalar.
🏥 Demanda vs Capacidade Médica

Comparação entre:

quantidade de consultas;
quantidade de médicos por especialidade.
Objetivos:
identificar gargalos operacionais;
analisar sobrecarga médica;
apoiar decisões de contratação.
📈 Principais Insights
🚨 Emergência apresenta alta taxa de no-show

Possível desperdício de recursos hospitalares e impacto em atendimentos urgentes.

Recomendação:

Implementar sistema de confirmação automática via WhatsApp ou SMS.

📅 Consultas possuem alto índice de cancelamento

Pode indicar:

insatisfação;
problemas de agendamento;
demora no atendimento.
Recomendação:

Revisar processo de agendamento e tempo de espera.

leitura dos arquivos CSV;
tratamento de datas;
limpeza de dados;
junção de tabelas com merge;
criação de métricas e indicadores;
análise exploratória.
👨‍⚕️ Dermatologia possui alta demanda por médico

A especialidade apresenta elevado número de consultas por profissional.

Recomendação:
redistribuir carga horária;
avaliar contratação de novos médicos.
📉 Existe sazonalidade na receita

Alguns meses apresentam queda significativa de faturamento.

Recomendação:
campanhas preventivas;
ações de retenção;
planejamento de férias em períodos de baixa.
📌 Indicadores Criados
Receita total
Receita mensal
Ticket médio
Taxa de no-show
Taxa de cancelamento
Consultas por especialidade
Consultas por médico
Receita por especialidade
🎯 Habilidades Demonstradas

Este projeto demonstra conhecimentos em:

análise exploratória de dados;
manipulação de dados com Pandas;
visualização de dados;
joins e relacionamento de tabelas;
criação de KPIs;
análise de negócio;
storytelling com dados.
🚀 Possíveis Melhorias Futuras
criação de dashboard no Power BI;
previsão de demanda com Machine Learning;
análise preditiva de no-show;
deploy do projeto;
automação de relatórios.
