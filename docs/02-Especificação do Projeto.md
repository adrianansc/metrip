# Especificações do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Documentação de Contexto.md"> Documentação de Contexto</a></span>

O propósito de desenvolver esse aplicativo partiu do pressuposto de que não existe um aplicativo de gestão de viagens capaz de suprir as necessidades básicas de viajantes de forma funcional e com o melhor custo-benefício em relação a outras possíveis soluções já existentes no mercado. Para detalhamento das demandas requeridas pelos usuários foram realizadas entrevistas com os verdadeiros amantes de uma estrada. 


## Personas

As personas a seguir nos ajudaram a entender o problema e levantar os pontos primordiais para início do desenvolvimento desta solução. 

| nº |NOME| IDADE  |OCUPAÇÃO |LOCALIZAÇÂO| APPS UTILIZADAS | MOTIVAÇÕES| FRUSTAÇÔES| HOBBIES|
|----|----|--------|----------|-----------|-----------------|------------|----------|---------|
| 01 | Théo Granjeiro Cavalheiro | 40 anos | Analista de Vendas| Ubá -MG | Uber, Ifood, Spotify, Kayak |	Desejo de conhecer o mundo.| Dificuldade em guardar dinheiro.| Andar de moto, viajar, conhecer pessoas, assistir canais de viagens.|
| 02 | Joana Galindo Mascarenhas | 65 anos| Professora de História| Cuiabá - MT | Instagram, Netflix, Amazon Prime, Kindle| Auto estima para viajar sozinha e vontade de conhecer o mundo | Depender dos outros | Filmes e séries, Ioga , Ler, Pintura |
|03| Lilian Cidreira Laranjeira | 25 anos| Arquiteta | Americana -SP | Instagram, Whatsapp, AutoCad , Airbnb, Booking | Conhecer as diferentes arquiteturas e culturas | Visitar uma cidade histórica e ver que sua cultura foi perdida. | Academia, cursos e palestras, fotografia, séries| 
|04| Marcos Teixeira Sales | 61 anos | Advogado | Recife-PE|	WhatsApp, Ifood, Booking, Skyscanner |  Fazer viagens pelo Brasil. | A perda de sua esposa que acompanhava-o em todas as viagens.  | Marcenaria DIY, Leitura, cursos e palestras, fotografia, caminhada com seu cachorro | 
|05| Ricardo Feliciano | 35 anos| Empresário autônomo | Florianópolis -SC| Instagram, Canva, Whatsapp, Snapseed | Fazer o que mais gosta e não ter rotina  | A perda do seu cachorro que lhe acompanhava em todas as suas viagens  | Surfar , dirigir sem destino, fotografia, corrida de rua

## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

| EU COMO... `PERSONA` | QUERO/PRECISO ... `FUNCIONALIDADE` |         Dúvidas        | PARA ... `MOTIVO/VALOR` |
|---------------|---------------------|----------------------------|------------------|
| Théo Cavalheiro  | Fazer um tour com a namorada por vários países do mundo | Não sabe como encontrar locais satisfatórios com bom custo-benefício. | Se distrair da rotina cansativa e repetitiva sempre nos mesmos locais. |




## Requisitos

O escopo funcional do projeto é definido por meio dos requisitos funcionais que descrevem as possibilidades interação dos usuários, bem como os requisitos não funcionais que descrevem os aspectos que o sistema deverá apresentar de maneira geral. Estes requisitos são apresentados a seguir: 

### Requisitos Funcionais

A tabela a seguir apresenta os requisitos do projeto, identificando a prioridade em que os mesmos devem ser entregues. 

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-01 | O aplicativo deve permitir ao usuário cadastrar-se com um login e senha. | Alta |
|RF-02 | O app deve conter um formulário para criação de registro de viagem. | Alta |
|RF-03 | O app deve permitir visualizar detalhes dos registros criados | Baixa |
|RF-04 | O app deve permitir editar os dados dos registros criados | Baixa |
|RF-05 | O app deve permitir excluir os dados dos registros criados | Baixa |
|RF-06 | O app deve permitir ao usuário anexar uma foto para complementar o cadastro de um registro de viagem. | Baixa |
|RF-07 | O app deve permitir a emissão de um relatório com as informações | Média |
|RF-08 | O app deve mostrar registros criados por outras pessoas na tela inicial | Média |
|RF-09 | O app deve permitir ao usuário buscar registros de locais específicos. | Baixa |
|RF-10 | O app deve conter um menu de navegação com indexação para as telas.  | Baixa |


### Requisitos não Funcionais

A tabela a seguir apresenta os requisitos não funcionais que o projeto deverá atender

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-01 | O aplicativo deverá apresentar um layout padrão para todas as telas, podendo ser criado ou utilizado um existente. |  |
|RNF-02 |O aplicativo deverá ser responsivo, permitindo a visualização em um celular de forma adequada. |  |
|RNF-03 |O aplicativo deverá ter uma fonte padrão para todas as escritas, com alterações apenas no tamanho. |   |
|RNF-04 |A aplicação deve ser intuitiva, de fácil utilização e entendimento, descartando a necessidade de treinamentos. |  |
|RNF-05 |A aplicação deve ser compatível com as últimas versões dos sistemas operacionais do Android e IOS. |   |
|RNF-06 |A aplicação deve possuir uma interface limpa, contendo somente elementos que serão utilizados naquela tela.  |   |
|RNF-07 |A aplicação deve ser disponibilizada por meio das principais lojas de aplicativo do mercado (Google Play, ITunes, etc...). |   |


## Restrições

As questões que limitam a execução desse projeto e que se configuram como obrigações claras para o desenvolvimento do projeto em questão são apresentadas na tabela a seguir. 

|ID| Restrição                                             |
|--|-------------------------------------------------------|
| RE-01 |O projeto deverá ser entregue no final do semestre letivo, não podendo extrapolar a data de 22/06/2022. |
| RE-02 | O aplicativo deve se restringir às tecnologias de desenvolvimento mobile. |
| RE-03 | A equipe não pode subcontratar o desenvolvimento do trabalho. |


