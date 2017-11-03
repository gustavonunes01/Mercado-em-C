***********************************************************************************
*  Nome do programa: MercES v1.                                                   *
*  Autor: Gustavo H. N. Santos.                                                   *
*  Data: 24/02/2017.                                                              *
*  Função Global:                                                                 *
*   Este software é para um super mercado, para consultar e inserir estoque e     *
*   vender suas mercadorias em estoque.                                           *
*  Linguagem de Implementação: C.                                                 *
***********************************************************************************
Projeto do programa:

Primeiro menu com opção de estoque e venda"

*SALDO INICIAL R$3000,00*
*ANTES DE INICIAR TEM QUE COLOCAR O NOME DO FUNCIONARIO*

*Estoque deve ter mais um sub menu, com a opção de inserir um produto no estoque.
	Quando inserir um produto no estoque devesse tirar do saldo.
	obs: o saldo deve ser feito em ponteiro. para poder ser alterado.
	Sub menu, "CONSULTAR ESTOQUE" (lista código, nome, quantidade no estoque e preço
de todos os produtos).
	Sub menu, Consultar o saldo do caixa. (o saldo do caixa aumenta com uma venda e diminui
quando são inseridos novos produtos no estoque)

*Venda na opção de venda deve aparecer os produtos do estoque contendo todos os
dados do estoque codigo do produto, quantidade e valor.(nessa parte do menu de venda deve
ter uma outra opção de "Começar venda")
	No menu "Começar venda" para realizar uma venda é necessário ver se o
produto tem o estoque necessário para a venda, se não tiver, uma mensagem deve ser
dada ao cliente). A venda deve ter um acréscimo de 25% ao valor do estoque (lucro do
comerciante) e a venda deve ser adicionada ao saldo. A venda deve ter um acréscimo de 25% ao valor do estoque (lucro do
comerciante) e a venda deve ser adicionada ao saldo. int venda (int cod, float *saldo).
