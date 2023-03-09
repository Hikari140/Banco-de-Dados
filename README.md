# Banco-de-Dados
Projeto Individual do Módulo 4 

A Resilia está pensando em lançar um novo sistema de
acompanhamento e para isso precisa de ajuda para modelar um
banco de dados que vai armazenar seus cursos, turmas e alunos.

##

## Perguntas

-  Existem outras entidades além dessas três?
> Além de curso, turma e alunos, existem também as seguintes entidades:
>- professor
>- unidade

- Quais são os principais campos e tipos?

> O banco de dados possui as seguintes tabelas:

### Aluno
A tabela aluno armazena informações sobre os alunos, incluindo:

>- `Nome_aluno:` chave primária do registro de aluno (Vachar)
>- `Idade:` idade do aluno (Tinyint)
>- `CPF:` cpf do aluno (Char)
>- `Sexo:` sexo do aluno (Char)
>- `Endereco:` endereço do aluno (Varhcar)
>- `Email:` email do aluno (Varchar)
>- `Telefone:` telefone do aluno (Varchar)

### Curso
A tabela curso armazena informações sobre os cursos oferecidos, incluindo:

>- `Nome_curso:` chave primária do registro de curso (Vachar)
>- `Datadocurso:` data de início e término do curso (Datetime)
>- `Preço:` preço do curso (INT)

### Unidade
A tabela unidade armazena informações sobre as unidade oferecidas, incluindo:

>- `Nome_unidade:` chave primária do registro de unidade (Vachar)
>- `Endereco:` endereço da unidade (Varhcar)
>- `Telefone:` telefone da unidade (Varchar)
>- `Email:` email da unidade (Varchar)

### Professor
A tabela aluno armazena informações sobre o professor, incluindo:

>- `Nome_professor:` chave primária do registro de professor (Vachar)
>- `Idade:` idade do professor (Tinyint)
>- `CPF:` cpf do professor (Char)
>- `Sexo:` sexo do professor (Char)
>- `Endereco:` endereço do professor (Varhcar)
>- `Email:` email do professor (Varchar)
>- `Telefone:` telefone do professor (Varchar)
>- `Formação:` formação do professor (Varchar)

### Turma
A tabela aluno armazena informações sobre a turma, incluindo:

>- `Horario:` chave primária do horario de aula da turma (Time)
>- `Vagas:` chave primária do horário de número de vagas da turma (INT)
>- `Nome_aluno:` chave estrangeira associado ao registro de aluno (Vachar)
>- `Nome_curso:` chave estrangeira associado ao curso (Vachar)
>- `Nome_unidade:` chave estrangeira associado a unidade (Vachar)
>- `Nome_professor:` chave estrangeira associado ao professor (Vachar)

- Como essas entidades estão relacionadas?

> São entidades com dados dos alunos, professores, curso e unidade, que ligam a formação da turma.
