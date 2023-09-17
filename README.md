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

![Diagrama de casos de uso do sistema](/image/diagramn.PNG)

# HomePage

Vimos anteriormente que as partes **Aluno** e **Professor** são basicamente **Pessoas Físicas**, e **Professor** *(quando possui CNPJ como microeempreendedor autonomo)* e **Fornecedor** são **Pessoas Juridicas**, logo, o acesso ao sistema se dá pelas 3 entidades mencionadas acima atravéz da pagina institucional da Universidade.

![Pagina Principal](/image/hp.PNG)

## Cadastro ##

A pagina de cadastro é acionada atravez do Link **Clique Aqui** após o Aluno, Professor ou Fornecedor clicar em seus respectivos links.

## Acesso ##



Após o usuario clicar em sua função correspondente (Aluno, Professor ou Fornecedor), a parte de login do sistema é acionada, direcionando aos correspondentes:

![Paginas de Login](/image/logins.PNG)

Quando o login é feito com sucesso, suas respectivas paginas de acesso são exibidas com suas devidas funções/metodos:

![Paginas de Login](/image/acessos.PNG)



# Link do Prototipo #

[Clique aqui para baixar (requer a aplicação FIGMA para visualizar)](/G5-FINAL.fig)


