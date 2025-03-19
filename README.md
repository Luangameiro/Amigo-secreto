# Amigo-secreto
Alura | Challenge amigo secreto
Objetivo:
Neste desafio, você desenvolverá uma aplicação que permita aos usuários inserir nomes de amigos em uma lista para, em seguida, realizar um sorteio aleatório e determinar quem é o "amigo secreto".

Instruções
O usuário deverá adicionar nomes por meio de um campo de texto e de um botão "Adicionar".

Os nomes inseridos serão exibidos em uma lista visível na página, e ao finalizar, um botão "Sortear Amigo" selecionará um dos nomes de forma aleatória, exibindo o resultado na tela.

Funcionalidades:
Adicionar nomes: Os usuários escreverão o nome de um amigo em um campo de texto e o adicionarão a uma lista visível ao clicar em "Adicionar".

Validar entrada: Se o campo de texto estiver vazio, o programa exibirá um alerta solicitando um nome válido.

Visualizar a lista: Os nomes inseridos aparecerão em uma lista abaixo do campo de entrada.

Sorteio aleatório: Ao clicar no botão "Sortear Amigo", um nome da lista será selecionado aleatoriamente e exibido na página.

Tarefas especificas:

 Crie um array para armazenar os nomes.

linha 1 -->let listaAmigos = [];

 Desenvolva uma função que permita ao usuário inserir um nome no campo de texto e adicioná-lo à lista de amigos criada anteriormente.

linha 3 á 38 -->function adicionarAmigo(){}

 Escreva uma função que selecione aleatoriamente um dos nomes armazenados no array amigos

linha 57 á 67 -->function sortearAmigo(){}

 Crie uma função que percorra o array amigos e adicione cada nome como um elemento <li> dentro de uma lista HTML,use innerHTML para limpar a lista antes de adicionar novos elementos.

linha 41 á 50 -->function exibirAmigos(){}.

🔄 Mudanças
Adição de um botão novo sorteio.

Ao invés de estático a cor do botão sortear só terá cor e estará habilitado a partir de dois nomes adicionados.

O adicionar agora tem cor igual ao sortear ao passar o mouse encima.

A cor do amigo sorteado foi mudada para azul (#4B69FD) para familiarização das cores.
