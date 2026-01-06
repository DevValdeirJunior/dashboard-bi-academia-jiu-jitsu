📊 Projeto de Business Intelligence – Academia de Jiu-Jitsu 📌 Visão Geral Este projeto foi desenvolvido no contexto acadêmico com o objetivo de aplicar, na prática, conceitos de Business Intelligence (BI) utilizando Power BI, desde a coleta dos dados até a entrega de dashboards estratégicos para apoio à tomada de decisão. O cenário do projeto simula uma academia de Jiu-Jitsu que realizava seus controles de forma manual (anotações em caderno). A partir disso, foi realizado um trabalho completo de estruturação dos dados, modelagem analítica e visualização, transformando informações brutas em insights gerenciais.
🎯 Objetivos do Projeto:
*Estruturar dados operacionais em um modelo analítico*
*Implementar um processo completo de ETL (Extração, Transformação e Carga)*
*Definir e calcular KPIs relevantes para o negócio*
*Criar dashboards interativos no Power BI*
*Publicar e atualizar os dados via Gateway*
*Capacitar o gestor da academia no uso do Excel e Power BI Online*
📂 Fonte de Dados Formato: Planilha Excel Origem: Dados operacionais da academia Processo adotado: Criação de uma planilha padronizada Organização das informações antes registradas manualmente Treinamento do responsável pela academia para preenchimento correto
🔄 Processo ETL (Power Query) Extração Importação direta da planilha Excel para o Power BI Transformação Limpeza de dados inconsistentes Padronização de datas e valores Criação de colunas derivadas Tratamento de valores nulos Normalização das tabelas Carga Dados carregados em um modelo relacional otimizado para análise
🧩 Modelagem de Dados O projeto utiliza modelagem dimensional, seguindo boas práticas de BI: Tabelas Fato Fato_Matriculas Fato_Pagamentos Fato_Presencas Tabelas Dimensão Dim_Alunos Dim_Plano Dim_Tempo Dim_Turma Essa abordagem melhora: Performance Escalabilidade Clareza analítica
📐 Medidas DAX Foram criadas medidas DAX para cálculo de indicadores estratégicos, como: Total de Alunos Ativos Receita Total Ticket Médio Taxa de Inadimplência Crescimento de Matrículas Alunos por Plano Retenção de Alunos As medidas permitem análises dinâmicas por período, plano e turma.
📊 Dashboards Os dashboards foram projetados com foco em gestão e tomada de decisão, utilizando: Cartões de KPIs Gráficos de linha (evolução temporal) Gráficos de barras e colunas Segmentações (filtros interativos) Layout limpo e orientado ao usuário final
☁️ Publicação e Gateway Por que Gateway? Atualização automática dos dados Integração segura com a planilha local Simplicidade e baixo custo Ideal para pequenos negócios Power BI Online Publicação do relatório Compartilhamento dos dashboards Treinamento do gestor para visualização e uso dos relatórios
🧠 Definição de KPIs:
Os KPIs foram definidos com base em entrevistas com o responsável pela academia, focando em perguntas como:
Quantos alunos ativos temos hoje?
Qual plano gera mais receita?
Existe queda de alunos em determinados meses?
Qual o faturamento mensal?
Quantos alunos estão inadimplentes?
Essas perguntas guiaram todo o processo analítico.
🛠️ Tecnologias Utilizadas:
Power BI Desktop
Power BI Service
Power Query
DAX
Microsoft Excel
📚 Aprendizados:
Aplicação prática de BI em um cenário realista
Importância da modelagem de dados
Transformação de dados operacionais em insights estratégicos
Comunicação entre área técnica e negócio
Uso profissional do Power BI do início ao fim
👨‍🎓 Contexto Acadêmico:
Projeto desenvolvido como parte das atividades da faculdade, integrando teoria e prática, com foco em análise de dados, inteligência de negócios e visualização de informações para suporte à gestão.
🚀 Considerações Finais:
Este projeto demonstra a capacidade de traduzir necessidades de negócio em soluções analíticas, utilizando ferramentas amplamente adotadas pelo mercado. Ele reflete domínio técnico, visão estratégica e boas práticas em Business Intelligence.
