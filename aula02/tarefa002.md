## Tarefa 002 - 28/07/2021 - Pesquisa Rest API

1. Elaborar uma pesquisa sobre o tema "_Rest API_".
2. Elaborar um texto de pelo menos uma página, descrito com suas próprias palavras, destacando:
* As definições dos conceitos envolvidos;
* As principais características deste conceito (pelo menos umas cinco).

Uma Api(Application Programming Interface) é um conjunto de regras que 
atua como software intermediário que dita como é feita a comunicação 
entre softwares. Já uma REST API é uma api que está em conformidade com 
o REST(Representational State Transfer). Ou seja, a API permite um 
programa ou serviço consultar informações de outros programas ou 
serviços, caracterizando uma relação Cliente(quem requisita) e Servidor
(quem possui a informação requisitada). 

Entre os conceitos que envolvem o funcionamento de uma REST API temos:
1. Interface uniforme;
2. Desacoplamento cliente-servidor;
3. Apátrida;
4. Arquitectura do sistema em camadas;
5. "Cacheabilidade".

1- Todos os pedidos de API para o mesmo recurso devem ter a mesma estrutura, independentemente do requisitante dessa API.
 Os recursos não devem ser demasiado grandes mas devem conter todas as informações que o cliente possa necessitar.

2- Da mesma forma, uma aplicação servidor não deve modificar a aplicação cliente a não ser passá-la para os dados solicitados via HTTP.

3- As APIs necessitam apenas das informações necessárias para o processamento da requisição, não instanciando nenhuma sessão no servidor, nem possibilitando que o mesmo salve dados sobre o cliente.

4- A API é composta de forma que nem o servido e nem o cliente tenham acesso um com o outro, de forma que se considera que ambos tenham várias camadas para tal.

5- As informações deverão ser  salvas no cache de um dos dois lados. O servidor armazena as informações necessárias para a requisição do cliente aumentando assim o desempenho da comunicação.