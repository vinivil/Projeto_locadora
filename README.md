# Projeto_locadora
This is a project done concurrently with the course of logic and logarithms and it was done with the purpose of evaluating my knowledge in python programming and evaluating my problem solving skills.

# DESCRISPTION 

A Locadora de fitas cassete e DVDs ACME está resistindo bravamente ao tempo e mantendo o seu negócio funcionando. Ela precisa criar um sistema para registro de usuários e estoque de fitas e DVDs, que apresente relatórios de empréstimo, mostrando se algum cliente está atrasado na devolução dos objetos alocados. Vamos ajudar a empresa desenvolvendo o sistema?

# Etapas:
# 1) Desenvolva uma ou mais funções em python que recebe o nome do cliente, o CPF e o RG;
Armazene as informações do cliente em um dicionário, utilizando como chave o CPF;
Crie um arquivo clientes.csv e grave os dados dos clientes no seguinte formato, separado por “;” com os campos Nome, RG, CPF.


# 2) Desenvolva uma ou mais funções em python que será responsável por controlar as informações das fitas e DVDs.
Deverá haver uma função de cadastro que recebe os seguintes dados, tipo (DVD,Fita), código do produto, Nome do Filme (Título),Ano de lançamento. Estes dados deverão inicialmente ser armazenados em um dicionário do python e depois ser persistido no arquivo filmes.csv, separados por “;” na seguinte ordem código,tipo,nome do filme, ano de lançamento.


# 3) Desenvolva uma ou mais funções para realizar a alocação das fitas e DVDs. Esta função deverá receber o nome do usuário, o código do item emprestado e a data do empréstimo. Os dados deverão ser armazenados no arquivo empréstimos.csv


Desenvolva uma função que irá apresentar baseado no arquivo empréstimos.csv, quais usuários estão atrasados na devolução. O relatório deverá ter o seguinte formato:


CPF                Nome             Título            Empréstimo  Situação        Dias

76744           Francisco      Jumanji          11/01/2020   Atrasado      100



A partir de 7 dias será considerado empréstimo em atraso.
