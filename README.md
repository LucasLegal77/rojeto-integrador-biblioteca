# 📚 Sistema de Gerenciamento de Biblioteca Escolar

Este é o projeto integrador das disciplinas de Banco de Dados e Programação C do 1º Ano do Ensino Médio Técnico.

---

## 📋 Plano de Análise

### 1. Qual problema será resolvido?
O sistema resolverá a falta de controle sobre os livros da biblioteca da escola. Atualmente, o controle é manual, o que gera perda de livros, atrasos nas devoluções e dificuldade para os alunos saberem se um livro está disponível.

### 2. Quem utilizará o sistema?
* **Administrador (Bibliotecário):** Responsável por cadastrar livros, alunos e registrar os empréstimos e devoluções.
* **Usuário Comum (Aluno):** Pode consultar a disponibilidade dos livros no acervo.

### 3. Quais entidades existirão no Banco de Dados?
* **Aluno:** ID_Aluno, Nome, Matrícula, Turma.
* **Livro:** ID_Livro, Título, Autor, Ano_Publicacao.
* **Empréstimo:** ID_Emprestimo, ID_Aluno, ID_Livro, Data_Retirada, Data_Devolucao.

### 4. Quais funcionalidades são essenciais para o MVP?
* Cadastro de novos alunos e livros.
* Registro de empréstimos.
* Listagem de livros disponíveis e emprestados.
