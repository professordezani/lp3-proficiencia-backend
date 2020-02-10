# Exame de Proficiência
## Prof. Dr. Henrique Dezani

Desenvolva os exercícios abaixo utilizando a linguagem de programação JavaScript.

Você foi contratado para desenvolver uma aplicação web ou mobile para uma distribuidora de produtos. O sistema é simples e consiste em alterar a quantidade dos produtos cadastrados em estoque. Para tanto, você precisará:

1. Criar uma API REST que seja capaz de retornar os produtos cadastrados (nome, id e quantidade) e de alterar a quantidade de um produto específico. Considere utilizar os seguintes endpoints:

GET http://localhost:3000/produtos
PUT http://localhost:3000/produtos/1

Considere utilizar uma lista estática em memória para armazenar e manipular os produtos.

2. Criar uma aplicação web ou mobile usando as bibliotecas React ou React Native, que seja capaz de consumir a API REST (Exercício 1). Deseja-se que o sistema seja de simples manuseio e, portanto, deverá contemplar as duas telas descritas a seguir:

- Na tela inicial deverá ser exibida a lista de todos os produtos. Ao clicar num produto, a tela de alteração deverá ser exibida com os dados do produto selecionado.
- Na tela de alteração de produto deverá haver um caixa de texto para entrada da quantidade do produto, já preenchida com o valor inicial. O usuário poderá então alterar o valor e clicar no botão Salvar. Ao Salvar, o sistema deverá invocar a API REST para realizar a tarefa e voltar para a tela inicial.
