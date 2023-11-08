# Projeto de Análise de Dados com Python e SQL

Este projeto visa a análise de um conjunto de dados contendo informações de pacientes que desenvolveram ou não diabetes. A atividade principal consiste em gerar uma amostra de dados com pacientes com mais de 50 anos e, para cada um deles, indicar em uma nova coluna se o paciente está normal (índice de massa corporal menor que 30) ou obeso (índice de massa corporal maior ou igual a 30). Após a classificação, os dados serão transformados e salvos em um novo arquivo CSV para posterior análise por um Cientista de Dados.

## Fonte dos Dados

Os dados utilizados neste projeto foram obtidos no seguinte link: [Pima Indians Diabetes Database](https://www.kaggle.com/uciml/pima-indians-diabetes-database).

## Passos do Projeto

Este projeto será dividido em etapas para facilitar a compreensão e execução:

1. **Carregamento dos Dados com Python:**
   - Os dados iniciais serão carregados utilizando a linguagem Python, geralmente com a ajuda de bibliotecas como Pandas.

2. **Criação de uma Amostra de Pacientes com Mais de 50 Anos:**
   - Será feita a seleção de pacientes com idade superior a 50 anos a partir dos dados carregados.

3. **Classificação de Pacientes como Normal ou Obeso:**
   - Será criada uma nova coluna que indicará se o paciente está normal ou obeso, com base no índice de massa corporal (IMC).

4. **Transferência dos Dados para um Banco de Dados:**
   - Os dados serão copiados para um banco de dados SQL para permitir o uso da linguagem SQL nas próximas etapas.

5. **Transformações SQL:**
   - Utilizando comandos SQL, os dados serão transformados para atender aos critérios de classificação dos pacientes.

6. **Recuperação dos Dados Transformados:**
   - Os dados transformados no banco de dados SQL serão recuperados e copiados de volta para um dataframe do Pandas.

7. **Salvamento dos Resultados em um Arquivo CSV:**
   - Os dados finais, com a classificação de pacientes normal ou obesos, serão salvos em um novo arquivo CSV.

## Requisitos

Para executar este projeto, você precisará das seguintes bibliotecas e ferramentas:

- Python (com Pandas e outras bibliotecas relevantes)
- Banco de Dados SQL (como SQLite, MySQL ou PostgreSQL)
- Conhecimento em SQL para as transformações necessárias
- Arquivo de dados disponível no link fornecido

## Execução do Projeto

Você pode seguir as etapas descritas neste README para executar o projeto ou adaptar o código conforme necessário. Lembre-se de que este projeto é uma análise de dados e envolve a manipulação de dados sensíveis, portanto, é importante garantir a segurança e conformidade dos dados em todas as etapas.

Ao concluir as etapas, você terá um arquivo CSV contendo a classificação de pacientes como normais ou obesos, pronto para análise posterior.

Este README serve como um guia geral para o projeto. Certifique-se de fornecer documentação detalhada e comentários em seu código para tornar o processo transparente e compreensível para outros envolvidos no projeto.
