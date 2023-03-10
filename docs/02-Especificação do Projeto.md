# Especificações do Projeto

A definição exata do problema e os pontos mais relevantes a serem tratados neste projeto foi consolidada com a participação dos usuários em um trabalho de imersão feita pelos membros da equipe a partir da observação dos usuários em seu local natural e por meio de entrevistas. Os detalhes levantados nesse processo foram consolidados na forma de personas e histórias de usuários.das para realizar a especificações do projeto

## Personas

As personas levantadas durante o processo de entendimento do problema são apresentadas na Figuras que se seguem:

> - Andrea Gomes de 41 anos, é supervisora de RH e sócio-proprietária de uma distribuidora de bebidas na região de BH. Pensa em aumentar sua renda e ser dona do próprio negócio. Seu maior desafio atualmente é resolver problemas no gestão de estoque, controle de gastos e processos mal otimizados na empresa.

> - Vitor Pereira, 32 anos. Proprietário de uma distribuidora de bebidas em Betim, tem enfrentado problemas com estoque furado, compras desnecessárias e falta de produtos. Empreendedor desde os 28 anos, tem a sensação de que os dias são muito curtos para todas as suas demandas. Tem o desejo de se tornar o maior vendedor da região, alcançar estabilidade financeira e atender as demandas dos clientes.

> - Carlos Augusto tem 26 anos e trabalha como gerente de uma distribuidora de bebidas em Contagem, região metropolitana de Belo Horizonte. Ele busca soluções no mercado para melhorar a gestão de processos na sua empresa, onde detectou a existencia de estoque obsoleto, relatórios pobres e inexatos, além de compras desnecessárias. Seus anseios são ter o próprio empreendimento, estabilidade financeira e dar melhores condições para sua familia.

> - Camila torres é uma estudante desempregada de 23 anos que estuda os processos necessários para abrir uma distribuidora de bebidas. Com pouca experiência e capital, busca conhecer as principais falhas na gestão desse tipo de empreendimento para conseguir alcançar seu objetivo de dominar as ferramentas de gestão e ter sucesso financeiro.

## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Eu,Andrea Gomes, como administradora | Controlar acesso de funcionários aos relatórios de estoque e vendas da empresa. | Manter os dados atuais e confiáveis. |
|Eu, Andrea Gomes,  como administradora |Registrar produtos oferecidos pela loja (cadastrar, remover, incluir e visualizar dados) |Ser capaz de acompanhar a dinâmica de vendas e realizar compras assertivas, evitando gastos desnecessários. |
|Eu, Vitor Pereira, como administrador | Emitir relatórios de estoque | Fazer a reposição do estoque em tempo hábil para garantir o atendimento ao cliente. |
|Eu, Vitor Pereira, como administrador |Emitir relatórios de vendas | Acompanhar quais produtos estão sendo mais vendidos e elaborar estratégia de vendas para os que não têm boa saída. |
|Eu como estoquista |Registrar as mercadorias que chegam e saem do estoque. | Ter sempre atualizados os dados e quantidades das mercadorias para auxiliar nas tarefas do setor de vendas. |
|Eu como estoquista | Emitir relatório de estoque. | Emitir relatório de estoque. | Garantir que o próprio estoque seja renovado corretamente (controle de gastos). |
|Eu como vendedor | Registrar venda dos produtos. | Facilitar ao gestor da empresa obter visão de negócio para tomada de decisões. |
|Eu, Carlos Augusto, como gerente | Cadastrar funcionários do estabelecimento | Manter o quadro de funcionários ativo e atualizado. |

## Requisitos

O escopo funcional do projeto é definido por meio dos requisitos funcionais que descrevem as possibilidades de interação dos usuários, bem como os requisitos não funcionais que descrevem os aspectos que o sistema deverá apresentar de maneira geral. Estes requisitos são apresentados a seguir.

### Requisitos Funcionais

A tabela a seguir apresenta os requisitos do projeto, identificando a prioridade em que os mesmos devem ser entregues.

|ID       | Descrição do Requisito  | Prioridade |
|---------|-----------------------------------------|----|
|RF-01| O sistema deve permitir ao usuário controlar o acesso de funcionários responsáveis por emitir relatórios. | ALTA | 
|RF-02| O sistema deve permitir ao usuário cadastrar, incluir, visualizar e remover funcionários do quadro de empregados da loja.| ALTA |
|RF-03| O sistema deve permitir ao usuário cadastrar, incluir, visualizar e remover os produtos da loja. | ALTA | 
|RF-04| O sistema deve permitir ao usuário emitir relatório de estoque da empresa.| MÉDIA |
|RF-05| O sistema deve permitir ao usuário emitir relatório de vendas da empresa. | MÉDIA | 
|RF-06| O sistema deve permitir ao usuário registrar as vendas realizadas.| MÉDIA |
|RF-07| O sistema deve permitir ao usuário registrar as entradas e saídas dos produtos no estoque. | MÉDIA | 

### Requisitos não Funcionais

A tabela a seguir apresenta os requisitos não funcionais que o projeto deverá atender.

|ID        | Descrição do Requisito  |Prioridade |
|--------|-------------------------|----|
|RNF-01| O site deve ser publicado em um ambiente acessível publicamente na Internet (GitHub) | ALTA | 
|RNF-02| O site deve ser responsivo permitindo a visualização em um celular de forma adequada |  ALTA | 
|RNF-03| O site deve ter bom nível de contraste entre os elementos da tela em conformidade | MÉDIA | 
|RNF-04| O site deve ser compatível com os principais navegadores do mercado (Google Chrome, Firefox, Microsoft Edge) |  ALTA | 

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID   | Restrição                                             |
|-----|-------------------------------------------------------|
|RE-01| O projeto deverá ser entregue no final do semestre letivo, não podendo extrapolar a data de 19/06/2023.|
|RE-02| O aplicativo deve se restringir às tecnologias básicas da Web no Front-end e Back-end.|
|RE-03| A equipe não pode subcontratar o desenvolvimento do trabalho.|
