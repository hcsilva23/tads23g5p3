# Sistema WEB de Cadastro da Universidade G5
Andamento PIII do Grupo 5 de TADS - Senac 2023

# Início
Esse projeto tem como objetivo prototipar como seria um sistema simples com interface atrativa para cadastrar e fornecer acesso as entidades da universidade.

# As entidades
Como exigido, o projeto é dividido em 5 partes:
- Pessoa Física
- Pessoa Juridica
- Aluno
- Professor
- Fornecedor

## Observação sobre as partes acima! ##

Aluno e Professor possuem as mesmas informações de cadastro de uma pessoa física, enquanto Professor (quando não trabalha com CTPS assinada, mas sim usando seu cadastro de MEI) e fornecedor possuem as mesmas informações de cadastro de uma pessoa juridica. Então temos uma relação de heranças onde Aluno e Professor herdam de Pessoa Fisica, enquanto Professor e Fornecedor herdam de Pessoa Juridica. O que diferenciará o Professor seria o ID que ele fornecer, ja que a mascara de um CPF é diferente de um CNPJ no cadastro.

## Diagrama do caso acima ##

(inserir imagem do digrama de casos de uso)

# HomePage

(insira tela da home aqui)

## Acesso ##

A metade superior da pagina, alem de botões de acesso rapido, é a de acesso, onde o sistema exigirá como login o CPF ou CNPJ de quem deseja acessar (que seriam os IDs das identidades), e que dependendo de qual entidade ela é, será direcionada para seu respectivo acesso.

## Cadastro ##

Como ja apresentado em documento, vimos anteriormente que as partes **Aluno** e **Professor** são basicamente **Pessoas Físicas**, e **Professor** *(quando possui CNPJ como microeempreendedor autonomo)* e **Fornecedor** são **Pessoas Juridicas**, a HOMEPAGE possuirá 3 botões de cadastro, para Aluno, Professor e Fornecedor.


