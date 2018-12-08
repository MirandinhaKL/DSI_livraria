# DSI_livraria
Primeiro Trabalho da Disciplina de Desenvolvimento de Sistemas I

Orientações do professor: 

  O objetivo desta atividade de implementação é relembrar conceitos de orientação a objetos, com implementação Java. Você deve implementar em Java, a base para um sistema de uma livraria.

  O sistema deve conter uma interface Produto, que representa um contrato a ser implementado por todas as classes que representarem produtos da livraria. A princípio a livraria terá dois tipos de produtos, livros e revistas, sendo que livros podem ser ebooks ou livro físico.
  
  Deve haver um outro contrato chamado Promocional, sendo que para Revistas pode ser aplicado um desconto de no máximo 10%, para livro físico máximo de 5%, e para ebooks pode ser aplicado um desconto de no máximo 30%.
  
  O livro físico possui uma taxa de impressão agregada ao seu valor, de 5% do valor inicial do livro.
  
  Um livro deve obrigatoriamente ter um autor para que seja criado, enquanto uma revista deve obrigatoriamente ter uma editora para ser criado.
  
  Um autor deve ter nome, email e cpf.
  
  Uma editora deve ter um nome fantasia e um cnpj.
  
  Um livro deve ter nome, descrição, valor e autor.
  
  Crie um esboço deste sistema, e crie uma classe Main para testar as classes e métodos. 
  
  Utilize o padrão DAO para interação com banco de dados.
  
  Utilize conceitos revisados em aula, procurando deixar seu código com o menos possível de repetição de código e acoplamento.
  
  No método main da classe Main:
- criar um objeto revista; 
- criar um livro no banco de dados, 
- excluir um livro do banco de dados, 
- listar os livros cadastrados no banco de dados, e 
- visualizar os detalhes de um livro incluindo o nome do autor.
