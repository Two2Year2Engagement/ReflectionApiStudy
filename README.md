# ReflectionApiStudy

This Repo is to Study Reflection Api from Java.

How the Repo works:

-Every person who wants to save his study on this repo wil create a folder with her name/username and save all his study inside this folder, example:
root
  -willmenn
      -willmenn's solution
      

This Repo will serve to guide the Studies using the following questions:

1 - Obter classe de um objeto, e imprimir nome.

2 - Criar uma classe abstrata vazia, criar outra classe que extende dessa classe abstrata, qualquer nome serve. Criar um método que cria uma instância da classe filha, mas retorna com o tipo da classe pai, e atribuir em uma variável:
 
 -  A : classe abstrata
 
 -  B extende A : classe normal
 
 -  B.getInstance() -> retorna tipo A
 
 -  B b = B.getInstance();
 
 -  Imprimir:
 
 -  b.class

 -  b.getClass()

Qual a diferença de ".getClass()" e ".class"? 

3 - Criar um pacote qualquer no projeto, criar uma classe qualquer dentro do pacote. Qual o nome absoluto da classe?

4 - Utilizando a estrutura do exercício 3 (anterior), utilizar a string do nome absoluto da classe (ex: “pacote.subpacote.blah.Classe”) para pegar uma referência à classe (Class<?>) da sua classe. Restrições: não pode utilizar “.class” ou “.getClass()”.

5 - Uma vez que o exercício 4 esteja resolvido, quais são às 3 formas de obter “Class<?>” dos classes em java? 

  - A partir daqui vou me referir aos “Class<?>” como meta classe.

6 - Criar instância de uma classe qualquer, que não tenha nenhum parâmetro no construtor. Restrições: Não pode utilizar a palavra reservada “new”, obrigatório criar instância a partir de uma meta classe.

7 - Criar instância de uma classe qualquer, que tenha um construtor com parâmetros (2 ou mais). Restrições: Não pode utilizar a palavra reservada “new”, obrigatório criar instância a partir de uma meta classe.

8 - Chamar método que não retorna, ou recebe qq parâmetro, de um objeto qualquer. Restrições: Não pode utilizar a palavra reservada “new”, obrigatório criar instância a partir de uma meta classe. O nome do método só pode aparecer no código como String (ex: objeto tem método a, é proibido utilizar objeto.a(), a deve apenas poder aparecer se estiver dentro de uma string “a”).

9 - Mesma coisa que 8, mas recebendo 2 ou mais parâmetros.

10 - Mesma coisa que 9, mas fazer para um método que retorna algum valor, imprimir este valor no fim.

11 - Criar função “inspect”, que dado um objeto qualquer, essa função vai:

    - Imprimir nome da classe

    - imprimir seus campos, com as informações: visibilidade (public, private, etc), nome da classe do campo, com seu tipo genérico, na forma “List<String>”, ou se não tiver genérico, apenas “List”.

    - imprimir construtores, e os tipos de seus argumentos (em ordem)

    - imprimir métodos, com as informações: tipo de retorno, visibilidade, tipo dos parâmetros (em ordem). e se é estático ou não



If you have other question to contribute, send a pull request.
