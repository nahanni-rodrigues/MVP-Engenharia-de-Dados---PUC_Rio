# MVP-Engenharia-de-Dados---PUC_Rio
Esse repositório tem os arquivos envolvidos no desenvolvimento do MVP da disciplina de Engenharia de Dados da Pós Graduação em Ciência de Dados e Analytics da PUC-Rio. Este projeto visa criar um pipeline de dados, envolvendo a pesquisa, coleta, modelagem, ingestão, categorização e análise de dados dos candidatos.

O arquivo data_science_jobs.csv é o dataset utilizado para desenvolver a análise de dados na plataforma Databricks Community Edition. Os dados estão organizados em formato de tabela, onde apresenta as seguintes colunas:

| Atributo                | Descrição  |
|-------------------------|------------|
| **enrolle_id**          | Identificador exclusivo para cada candidato |
| **city**                | Código da cidade onde o candidato está localizado. |
| **city_development_index** | Pontuação do índice de desenvolvimento da cidade (escala de 0 a 1). |
| **gender**              | Gênero do candidato (masculino, feminino, outro). |
| **relevent_experience** | Se o candidato tem experiência relevante na área. |
| **enrolled_university** | Status de matrícula do candidato (período integral, meio período ou não matriculado). |
| **education_level**     | Nível de educação do candidato. |
| **major_discipline**    | Área de estudo (STEM, negócios, etc.). |
| **experience**         | Anos de experiência profissional. |
| **company_size**       | Tamanho da última empresa em que o candidato trabalhou. |
| **company_type**       | Tipo de empresa (por exemplo, Pvt Ltd, Startup, etc.). |
| **training_hours**      | Horas gastas em treinamento. |
| **target**             | Indicador binário (1 = procurando um novo emprego, 0 = não procurando). |

As perguntas desenvolvidas para analisar esse conjunto de dados são: 
1.	Perfil dos profissionais:  
•	Qual a distribuição de gênero dos candidatos?  
•	Qual o nível de formação mais comum entre os profissionais de ciência de dados?  
•	Qual a experiência média dos candidatos?  
•	Quantas pessoas já têm experiência relevante na área?  
2.	Fatores que Impactam a Contratação:  
•	O nível de educação influencia na intenção de trocar de emprego?  
•	Candidatos que fizeram mais horas de treinamento têm mais chances de mudar de emprego?  
•	Qual o impacto do tamanho da empresa na retenção de talentos?  
•	Empresas privadas (Pvt Ltd) perdem mais funcionários do que startups?  
3.	Localização e Desenvolvimento do Mercado:  
•	Em quais cidades há maior concentração de profissionais de ciência de dados?  
•	O índice de desenvolvimento da cidade (city_development_index) tem impacto na retenção de talentos?  
4.	Análises sobre Empresas  
•	Qual o porte das empresas que mais contratam profissionais de ciência de dados?  
•	Startups contratam mais profissionais juniores ou seniores?  
•	Empresas grandes (5000+ funcionários) investem mais em treinamento do que empresas pequenas?  

Todas as análises geradas estão descritas no arquivo PDF nomeado MVP Engenharia de Dados.
