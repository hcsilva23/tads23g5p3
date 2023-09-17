# Sistema WEB de Cadastro da Universidade G5
Andamento Projeto Integrador III do Grupo 5 de TADS - Senac 2023

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

Aluno e Professor possuem as mesmas informações de cadastro de uma pessoa física, enquanto Professor (quando não trabalha com CTPS assinada, mas sim usando seu cadastro de MEI) e Fornecedor possuem as mesmas informações de cadastro de uma pessoa jurídica. Então, temos uma relação de heranças onde Aluno e Professor herdam de Pessoa Física, enquanto Professor e Fornecedor herdam de Pessoa Jurídica. O que diferenciará o Professor será o ID que ele irá fornecer, já que a máscara de um CPF é diferente de um CNPJ no cadastro. 

## Diagrama do caso acima ##

![Diagrama de casos de uso do sistema](/image/diagramn.png)

# HomePage

Vimos anteriormente que as partes **Aluno** e **Professor** são basicamente **Pessoas Físicas**, e **Professor** *(quando possui CNPJ como microeempreendedor autonômo)* e **Fornecedor** são **Pessoas Jurídicas**, logo, o acesso ao sistema se dá pelas 3 entidades mencionadas acima através da página institucional da Universidade.

![Página Principal](/image/hp.JPG)

## Cadastro ##

A página de cadastro é acionada após o Aluno, Professor ou Fornecedor clicar em seus respectivos links.

![Passo Cadastro 1](/image/passocadastro1.JPG)

E em seguida através do Link **Clique Aqui**

![Passo Cadastro 2](/image/passocadastro2.JPG)

Assim, abrirá a página de cadastro de seu respectivo tipo de acesso, dos três possíveis: 

![Passo Cadastro 3](/image/cadastros.JPG)



## Acesso ##

Após o usuário clicar em sua função correspondente (Aluno, Professor ou Fornecedor), a parte de login do sistema é acionada, direcionando aos correspondentes:

![Paginas de Login](/image/logins.JPG)

Quando o login é feito com sucesso, suas respectivas páginas de acesso serão exibidas com suas devidas funções/métodos:

![Paginas de Login](/image/acessos.JPG)



# Link do Prototipo #

Para melhor abstração e visualização dos Protótipos que foram desenvolvidos no FIGMA:

[Clique aqui para baixar (requer a aplicação FIGMA para visualizar)](/Prototipo-Interface-UniversidadeG5-Final.fig)

ou [Clique aqui para acessar (requer cadastro no FIGMA)](https://www.figma.com/file/wjKrUEIHarYcgZsKqYYhxr/Prototipo-Interface-UniversidadeG5-(Final)?type=design&t=tSkDF0w4P34Bslvc-6)

## Integrantes do Projeto ##

* Antenor Pereira dos Santos
* Henrique Carvalho Silva
* Lívia Yuri Tanaka Castilho
* Luciene Gomes de Oliveira
* Marina Augusto de Moraes
* Nicoly de Jesus Jang
* Paulo Venício da Cunha M. Filho


