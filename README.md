# Case API veículos



Precisamos construir uma API para finalizar o processo de venda de veiculos.
Voce deverá desenvolver endpoints para: 
 - Um  para cadastrar uma venda 
 - Um consultar uma venda

O endpint de cadastro, devem receber os seguintes dados :

- Modelo do veiculo
- Data da venda
- Identificador único do veículo
- Marca do veículo
- Identificador do vendedor
- Identificador do cliente que fez a compra

Voce também deverá salvar na tabela de venda, o valor do veículo no momento da compra,
mas para isso voce devera consumir o endpoint de informacoes adicionais do veiculo
disponivel na URI  https://682f4733f504aa3c70f36f79.mockapi.io/stock/vehicle/vehicledetalhes ,
e recuperar o valor do veículo para salvar na tabela de vendas.

O time de negocio solicitou que a API pudesse permitir  a venda de veiculo com uma parametrização
de acordo com o tipo de combustivel( Electric, Hybrid, Gasoline... ) de uma forma dinamica
para campanhas de promoção.
Ex.: Durante essa semana  a API so podera efetuar vendas de veiculos eletricos, caso o veiculo
soolciitado para a venda nao seja eletrico a venda nao podera ser realiazada. Posteriormente, o time de negocio
pode querer permitr que a venda seja feita apenas de veiculo hibridos e a gasolina etc.
O tipo de combustivel e retornado na API de informacoes adicionais do veiculo
https://682f4733f504aa3c70f36f79.mockapi.io/stock/vehicle/vehicledetalhes


Para a  consulta, voce deverá implementar um  endpoint que retorne  todas as vendas, e permita ordenacao por
data da venda, e por marca do veículo.
E tambem deverá implementar um endpoint que consulte a venda pelo identificador único do veiculo.

Fique livre para implementar os endpoints da maneira que achar melhor, e definido
todos os requisitos tecnicos necessarios para a implementacao de uma API Rest,  simulando um caso real
de como voce implementaria essa APIna prática. Tambem pode ficar livre para usar a IDE e bibliotecas
que voce estiver mais familiarizado. 

Ao finalizar o teste, criei uma branch com seu nome e envie o codigo para esse repositorio







