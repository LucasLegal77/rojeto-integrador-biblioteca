# 📚 Sistema de Gerenciamento de Biblioteca Escolar

Projeto Integrador das disciplinas de Banco de Dados, Programação C e Educação Digital.
1º Ano do Ensino Médio Técnico.

---

## 🚀 Plano de Análise do Projeto

### 1. Qual problema será resolvido?
O sistema resolverá a falta de controle sobre os livros da biblioteca da escola. Atualmente, o controle é manual ou inexistente, o que gera perda de livros, atrasos nas devoluções sem aplicação de advertências e dificuldade para os alunos saberem se um livro está disponível ou não.

### 2. Quem utilizará o sistema?
* **Administrador (Bibliotecário):** Responsável por cadastrar livros, alunos e registrar os empréstimos e devoluções.
* **Usuário Comum (Aluno):** Poderá consultar a disponibilidade dos livros no acervo.

### 3. Quais entidades existirão no Banco de Dados?
* **Aluno:** ID_Aluno, Nome, Matrícula, Turma.
* **Livro:** ID_Livro, Título, Autor, Ano_Publicacao.
* **Empréstimo:** ID_Emprestimo, ID_Aluno, ID_Livro, Data_Retirada, Data_Devolucao_Prevista.

### 4. Quais funcionalidades são essenciais para o MVP?
* Cadastro de novos alunos.
* Cadastro de novos livros.
* Registro de empréstimo (vincular aluno ao livro).
* Listagem de livros disponíveis e livros emprestados.

---

## 👥 Integrantes da Dupla
* [Lucas Henrique]
* [João Guilherme]
