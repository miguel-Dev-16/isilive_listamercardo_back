# Sistema Lista de Mercado

## Reequisitos
- Ser capaz de gerenciar varias listas de mercado ( e marcar seu status como concluído ou não).
- Ser capaz de cadastrar produtos e consultalos.
- Ser capaz de incluir produtos nas listas e especificar suas quantidades, bem como marcar se o item já foi comprado ou não.
- Ser capaz de atribuir valores aos itens comprados para depois ter uma gestão dos custos da lista da lista.
- Ser capaz de adicionar quantidade (kg, litros, unidades, etc)

## Casos de Uso - Produto
### Cadastrar produtos
Informar o nome de um determinado produto e o sistema armazena no banco.
### Consultar produtos
Informar palavras chaves para consultar ou mesmo buscar produtos apartir de uma lista.
### Alterar dados de produtos
Basicamente alterar o nome do produto e temos sua efetivação no banco de dados.

## Casos de Uso - Lista
### Criação de listas
Criar uma nova lista, inserindo a data e o local onde foi feita a compra(nome do supermercado/feira, etc) 
### Apagar uma lista
Remover uma lista que foi criada por engano e remover todos os seus itens que foram criados.
### Inserção de itens na lista
Criar um item associando a uma lista e a um produto, bem como deixar disponivel a possibilidade de modificar quantidade e preço qeue foi pago.
### Alteração de itens da lista
Alterar apenas quantidade e preço pago e status.
### Remoção de itens da lista
poder remover um item que foi cadastrado na lista.
### Fechamento da lista
concluir a lista como sendo completa!, e gerar seu custo total a partir dos itens comprados.
