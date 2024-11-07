# Construindo um Esquema Conceitual para Banco De dados – OFICINA

Este repositório contém a resolução do desafio de construção de um Esquema Conceitual para Banco De dados - OFICINA. Este é um desafio de projeto do curso **Suzano - Análise de Dados com Power BI**.

Para a resolução deste projeto, foi definido a seguinte narrativa para o Projeto de Oficina:

- Sistema de controle e gerenciamento de execução de
ordens de serviço em uma oficina mecânica
- Clientes levam veículos à oficina mêcanica para serem
consertados ou para passarem por revisões periódicas
- Cada veículo é designado a uma equipe de mecânicos que
identifica os serviços a serem executados e preenche uma
OS com data de entrega.
- A partir da OS, calcula-se o valor de cada serviço,
consultando-se uma tabela de referência de mão-de-obra
- O valor de cada peça também irá compor a OS
- O cliente autoriza a execução dos serviços
- A mesma equipe avalia e executa os serviços
- Os mecânicos possuem código, nome, endereço e
especialidade
- Cada OS possui: n°, data de emissão, um valor, status e uma
data para conclusão dos trabalhos.
- Uma OS pode ser composta por vários serviços e um mesmo
serviço pode estar contido em mais de uma OS.
- Uma OS pode ter vários tipos de peça e uma peça pode
estar presente em mais de uma OS

A partir dessa narrativa inicial, foi proposto o desafio de criar um esquema conceitual do zero. A partir da narrativa fornecida você será capaz de criar todas as entidades, relacionamentos e atributos.

Foi entendido, no desenvolvimento desse diagrama, que a grande parte das informações principais do funcionamento deste esquema estão contidas e relacionadas na entidade de Ordem de Serviço.

Com isso, a resolução deste desafio está contido na imagem armazenada neste repositório.
