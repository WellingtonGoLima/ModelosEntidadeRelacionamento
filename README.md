CENARIO1-Construa o modelo Entidades-Relacionamentos a partir da seguinte descrição do sistema: Uma empresa de venda de automóveis retende implementar um sistema para gerir a informação relativa às operações de oficina efetuadas nos veículos dos seus clientes. O sistema de informação deverá permitir manter um registo histórico de todas as reparações efetuadas. A empresa pretende manter dos clientes a seguinte informação: código de identificação, nome, morada e telefone.

A empresa pretende também saber os veículos que um dado cliente teve ou tem e as datas em que foram adquiridos. Dos funcionários da oficina a empresa pretende manter a seguinte informação: código de identificação, nome, morada, telefone e categoria. O custo horário de mão de obra depende da categoria do funcionário e é definido através de uma tabela que é atualizada regularmente.

A empresa pretende saber para cada reparação: qual o veículo, qual o cliente, a data em que foi efetuada e o custo total da reparação. A empresa pretende também armazenar para cada separação as peças que foram utilizadas e o seu preço, bem como o tempo de mão de obra gasto por cada funcionário e o respectivo custo. A empresa pretende manter para as peças em armazém a seguinte informação: código de identificação, designação, custo unitário e quantidade em armazém.


CENARIO2-Construa o modelo Entidades-Relacionamentos a partir da seguinte descrição do sistema:
Considere um sistema de informação para a gestão de empreitadas. O sistema deverá registar:
·  Os recursos humanos associados a cada empreitada (identificação do técnico, número de
horas de trabalho e a especialidade).
·  As várias etapas de cada empreitada, estando associada a cada etapa o cumprimento de
um objetivo numa determinada data e a emissão da fatura respectiva.
·  O material (tipo e quantidade) usado em cada dia de empreitada. Uma empreitada pode subdividir-se noutros empreitadas, as quais devem ser geridas como empreitadas independentes. Alguns dos materiais usados pelas empreitadas são materiais especiais, para os quais é necessário fazer um seguro de transporte próprio, indicando o nome do condutor e a matrícula de veículo na qual será transportada.


CENARIO3-Construa o modelo Entidades-Relacionamentos a partir da seguinte
descrição do sistema: Pretende-se criar uma base de dados que
permita gerir a informação de um sistema de cartões de crédito de
uma entidade bancária. Neste banco existem vários tipos de cartões
de crédito com diferentes limites de crédito e condições de
pagamento.
Cada cliente pode solicitar para cada uma das contas que possui no
banco apenas um cartão de crédito. No entanto é de referir que uma
conta pode ter vários titulares pelo que podem ser emitidos
vários cartões sobre essa mesma conta.
Outro tipo de cliente do banco é aquele que embora não sendo titular
de uma conta possui um cartão de crédito. Estas situações acontecem
quando um titular de uma conta oferece um cartão de crédito a
terceiros.
Para cada cartão de crédito emitido é registado o tipo de cartão, a data
de emissão e o prazo de validade. Como referido anteriormente o
limite de crédito e as condições de pagamento dependem
do tipo de cartão de crédito.
Da mesma forma que uma conta bancária tem associado um saldo, a
cada cartão de crédito está associado um saldo que resulta do total
das despesas efectuadas com esse cartão e ainda não debitadas.

CENARIO4-Construa o modelo Entidades-Relacionamentos a partir da seguinte descrição do sistema:
Pretende-se criar uma base de dados que permita gerir uma parte da informação de uma clinica de saúde.
Fundamentalmente a base de dados deverá guardar a informação relativa aos doentes que frequentam a clínica (nome, morada, telefone e numero de beneficiário) e dos médicos que lá trabalham (nome, morada, contato e especialidade).
Para além disso o sistema deverá registar as marcações de consultas de cada paciente para um determinado médico sabendo que esse médico só pratica uma determinada especialidade. No entanto, na clinica um paciente pode obviamente consultar diferentes médicos para a mesma ou para diferentes especialidades.
O sistema deverá ainda para cada paciente e por especialidade permitir organizar uma ficha de informações que é atualizada sempre que um médico da especialidade observa esse paciente..
