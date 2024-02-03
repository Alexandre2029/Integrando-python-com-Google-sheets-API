# Desafio

Essa aplicação foi desenvolvida utilizando Python em conjunto a API do Google Sheets para realizar operações em uma planilha, como leitura e atualização de dados. 

1- Importa as bibliotecas necessárias do Google API.

2- Define as constantes SCOPES para as permissões da API, SAMPLE_SPREADSHEET_ID para o ID da planilha e SAMPLE_RANGE_NAME para o intervalo de células a serem lidas.

3- Implementa funções para calcular a situação do aluno (calculate_situation) com base na média de notas, número de faltas e total de aulas, e para calcular a nota para aprovação final  (calculate_naf) com base na média.

3- No método main(), verifica se há credenciais salvas no arquivo "token.json" e, se não houver, solicita ao usuário que faça login.

4- Utiliza a API do Google Sheets para obter os valores de uma planilha específica e realizar operações de cálculo de situação e nota para aprovação final para cada aluno.
Atualiza a planilha com as novas informações, incluindo a situação e a nota para aprovação final calculadas.
 
