Este Mini-Projeto faz parte do Curso "Microsoft Power BI para Business Intelligence e Data Science" da Data Science Academy, que busca analisar os dados de RH (Recursos Humanos) com o Power BI.

O Dashboard criado deve responder às seguintes perguntas de negócio:

1- Qual o total de funcionários atualmente na empresa?

2- Qual o tempo médio de experiência dos funcionários (em anos)?

3- Qual o total e percentual de funcionários do gênero masculino e feminino?

4- Qual a média salarial mensal?

5- Qual o total de funcionários por função?

6- Qual o percentual de funcionários disponíveis para fazer hora extra?

7- Qual o nível de envolvimento dos funcionários no trabalho considerando 4 categorias: Ruim, Baixo, Médio e Alto?

8- Este item não consta no Dashboard, mas foi calculado: Qual o total e o percentual de funcionários que devem receber promoção? Para isso foi aplicada à coluna “Anos Desde a última Promoção” a seguinte regra: Se o funcionário tiver 5 anos ou mais desde a última promoção, deve ter a promoção considerada. Caso contrário, a promoção não deve ser considerada agora.

Para isso foi realizada as seguintes etapas:

- Dashboard com KPIs e Filtros: Criação de uma visualização clara com métricas essenciais, como o total de funcionários, distribuição por gênero, experiência média e salário médio. Também foi inseridos gráficos de distribuição de função e envolvimento no trabalho, além de um filtro por idade.

- Uso de Medidas em DAX: Criação de medidas personalizadas para calcular métricas como porcentagem de funcionários por gênero e status de promoção, além de medidas para salário médio e outras estatísticas relevantes. Isso permite um controle mais dinâmico e específico nas análises.

- Transformações e Limpeza de Dados no Power Query: Aplicação de transformações importantes, como ajuste de tipos de dados e criação de colunas condicionais, incluindo uma coluna que define o status de promoção do funcionário, algo que facilita a análise de oportunidades de crescimento.
