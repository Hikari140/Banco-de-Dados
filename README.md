# Banco-de-Dados
Projeto Individual do Módulo 4 

A Resilia está pensando em lançar um novo sistema de
acompanhamento e para isso precisa de ajuda para modelar um
banco de dados que vai armazenar seus cursos, turmas e alunos.

##
### Perguntas

- Existem outras entidades além dessas três?

> Sim, foi adicionado também unidade e professor

- Quais são os principais campos e tipos?

> 'Nome_aluno' Varchar
    Idade Tinyint (3) not null,
    CPF Char (12),
    Sexo Char (10),
    Endereço Varchar (100) not null,
    Email Varchar (50) not null,
    Telefone Varchar (15)

- Como essas entidades estão relacionadas?

> São entidades com dados dos alunos, professores, curso e unidade, que ligam a formação da turma.
