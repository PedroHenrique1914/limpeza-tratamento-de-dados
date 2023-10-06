# Descrição do Projeto

O objetivo deste projeto consiste em corrigir a base de dados de uma instituição financeira

Inicialmente realizei observei a base de dados e realizei análises de algumas colunas individualmente

Após identificar os erros da base de dados, fiz as correções necessárias, que encontram-se abaixo e também no código

Listagem de correções realizadas:
​
1. Renomeação das colunas

2. Salários:
    
    2.1. substituição de valores nulos pela mediana
    
    2.2. substituição de outliers pela mediana

3. Gênero - padronização de valores e substituição de valores nulos pela moda (masculino)

4. Idade - substituição de idades fora do domínio (entre 18 e 120 anos) pela mediana

5. Exclusão de linhas duplicadas (clientes cadastrados mais de uma vez)

6. Estado - substituição de Estados fora do domínio (região sul) pela moda (RS)
