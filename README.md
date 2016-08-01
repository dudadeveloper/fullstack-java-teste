# Por que trabalhar na Lemontech

A Lemontech é uma empresa especializada no desenvolvimento de softwares que contribuem na Gestão das Viagens Corporativas.
Têm como principais objetivos, reduzir custos e tornar os processos mais dinâmicos.
O Sistema Lemontech, é utilizado por corporações e agências de viagens que buscam economia, eficiência e automação dos seus negócios.ditamos no poder da tecnologia para melhorar continuamente a vida das pessoas. 

Se você tem espírito e comportamento empreendedor, muita disposição e proatividade para trabalhar em uma empresa em franca expansão, você é um forte candidato :)

Como Desenvolvedor Full-stack você irá atuar no desenvolvimento de soluções em arquitetura Java Web MVC, Java EE, integrações com outros sistemas (SOAP, REST, JMS) e soluções escaláveis, participando de todo o processo de desenvolvimento, desde tomadas de decisões à codificação e testes.

# O que preciso fazer?

Vamos ser práticos e diretos, se você quer trabalhar conosco siga os passos abaixo:

* Faça um "fork" desse projeto para sua conta GitHub.
* Implemente o desafio descrito no tópico abaixo.
* Faça um push para seu repositório com o desafio implementado.
* Envie um email para (rh@lemontech.com.br) avisando que finalizou o desafio com a url do seu fork.
* Cruze os dedos e aguarde nosso contato.

# O desafio (Consulta de Solicitações de Viagens)

Você deverá criar uma aplicação consumidora de nossa API de webservice para consultar solicitações de viagens e persistir em banco de dados os dados de produtos Aéreos:

Endpoint: https://treinamento.lemontech.com.br/wsselfbooking/WsSelfBookingService?wsdl

Credenciais para autenticação: Seré enviada por email para o candidato.

Método a ser utilizado: pesquisarSolicitacao.

Arquitetura: Pode-se utilizar qualquer recurso da especificação JavaEE.

### Requisito

Consultar as solicitações de viagens filtrando pelos últimos 3 meses e separar apenas as que contenham produtos Aéreos.

Criar um banco de dados / tabela para persistir as informações da solicitação de viagem com as infromações básicas: Nome do Passageiro, CIA Aérea, Data/Hora de Saída e Chegada, Cidades de Origem e Destino.

Segregar o serviço de consulta ao WS e o de persistência no BD, imaginando que poderiam estar em um ambiente distribuído e após consulta ao Webservice a viagem possa ser enviada de alguma forma para um local onde o serviço que fará a persistência faça a leitura desses objetos e efetive a gravação no banco de dados.

Propor solução utilizando padrões e funcionalidades JavaEE.

### Arquitetura e documentação

No arquivo README do projeto explique o funcionamento e a arquitetura da solução adotada na sua implementação. Descreva também os passos para executar corretamente seu projeto.

### Avaliação

Entre os critérios de avaliação estão:

* Facilidade de configuração do projeto
* Performance
* Código limpo e organização
* Documentação de código
* Documentação do projeto (readme)
* Arquitetura
* Boas práticas de desenvolvimento
* Design Patterns
