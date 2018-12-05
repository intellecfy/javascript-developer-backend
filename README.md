#  Javascript Developer: Back-End

## Agora é hora de por a mão na massa. :)

Você poderá fazer o teste de duas formas, são elas:

* Criar uma API com autenticação por JWT utilizando algum framework NodeJS, ou
* Criar uma API utilizando uma arquitetura serverless na AWS.

## Instruções para o teste:

### API NodeJS:

- Crie uma API com os seguintes endpoints
	- login
	- diary
- O endpoint **/login** vai receber **username** e **password** e retornar um **JWT**.
- Você pode guardar o **username** e **password** em um banco como MongoDB ou no próprio arquivo .js.
- Para que o endpont **/diary** retorne **200** será necessário validar o **JWT** que será enviado pelo header.

**Dica**

Você pode selecionar um framework que te possibilite trabalhar com maior velocidade e de forma mais dinâmica. 
**Express, Restify,  FeathersJS e etc**

### API serverless AWS:

Se você optar por essa abordagem, você vai precisar criar uma conta gratuíta na AWS, criar a API e apresentar a solução por Skype.

Você deve utilizar:

- **Amazon Cognito** para autorizar o usuário
- **Amazon API Gateway** para criar o endpoint **{{domain}}/diary**
- **Amazon DynamoDB** para guardar a lista de diarios
- **AWS Lambda** para integrar os serviços

## Mais informações

- Documente sua API utilzando o Postman
- Diary JSON

```javascript
[{
	"date": "08-01-2015",
	"day": "Thursday",
	"tasks": [
		"Task 1",
		"Task 2"
		]
},
{
	"date": "09-01-2015",
	"day": "Friday",
	"tasks": [
		"Task 1"
	]
}]

```

## O que será avaliado:

- Se o código está claro, clean code na veia!
- Se está rodando sem erros.
- Atenção aos detalhes (Boas práticas, indentação, etc...)
- Se há testes unitários.
- Se há uma forma de testar o código, como Postman.
- Sua astucia e capacidade de resolver o problema

## Quando terminar:

Se escolheu a **API NodeJS**, suba seu projeto em algum gerenciador de repositório de software baseado em git e nos envio o link do projeto. No caso da **AWS**, assim que terminar entre em contato para marcar a apresentação por Skype.

**Vamos nos esforçar para dar um feedback caso você passe ou não, mas não poderemos garantir isso se recebermos uma quantidade muito grande de testes.**

Alguns links úteis:

- Express - <https://expressjs.com/pt-br/>
- Restify - <http://restify.com/>
- FeathersJS- <https://feathersjs.com/>
- Mochajs - <https://mochajs.org/>
- Postman - <https://www.getpostman.com/>
- AWS Cognito - <https://aws.amazon.com/pt/cognito/>
- AWS API Getway- <https://aws.amazon.com/pt/api-gateway/>
- AWS Dynamodb - <https://aws.amazon.com/pt/dynamodb/>
- AWS Lambda - <https://aws.amazon.com/pt/lambda/>

