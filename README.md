# Testes end to end com Cypress

## Bytebank

O Bytebank é um MVP de banco digital que está no início de suas atividades mas ainda falta muito que ser desenvolvido. 


</br>
<p align="center"> <img src="http://img.shields.io/static/v1?label=STATUS_GERAL&message=FINALIZADO&color=RED&style=for-the-badge" #vitrinedev/> </p>


# Testes end to end com Cypress
O Bytebank é um MVP de banco digital que está no início de suas atividades mas ainda falta muito que ser desenvolvido.


## 🔨 Funcionalidades do projeto
Faça esse curso de React e (React: escreva testes end to end com Cypress):
* Conheça o Cypress e as vantages de utilizá-lo para testar suas aplicações Front-end
* Saiba como instalar e utilizar o Cypress em seus projetos
* Escreva testes de ponta a ponta em suas aplicações React
* Crie comandos personalizados no Cypress
* Entenda como testar formulários e múltiplas páginas com o Cypress
* Entenda o que são as jornadas de usuário ao escrever testes
* Realize seus testes em diferentes navegadores e dispositivos móveis

Faça esse curso de React e (React: avançando em testes e2e com Cypress):
* Conhecer boas práticas de organização e escrita de testes no Cypress
* Compreender e realizar testes de API utilizando o Cypress
* Entender como utilizar mocks e stubs em testes de ponta a ponta
* Realizar testes com dados dinâmicos
* Escrever testes de jornada de usuários testando a integração de Front-end e Backend juntos
* Entender como proteger dados sensíveis em suas aplicações
* Testar recursos de suas aplicações em diferentes tamanhos de tela


## :bookmark_tabs: Técnicas e tecnologias utilizadas
As técnicas e tecnologias utilizadas pra isso são:

![Cypress](https://img.shields.io/badge/Cypress-17202C?style=for-the-badge&logo=cypress&logoColor=white)

![React](https://img.shields.io/badge/React-414141?style=for-the-badge&logo=react&logoColor=61DAFB)

![NodeJS](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)


## 📚Telas/Vídeos
[Imagem]


## 🛠️ Abrir e rodar o projeto
Baixar projeto:
- ` Baixar projeto api` git clone https://github.com/Amanda92Cortez/cypress-react-bytebank.git
- ` Configuração api` [Configuração API](api-bytebank/README.md)

Após baixar o projeto, você pode abrir com o **VSCode**. 
- ` Baixar npm pasta API ` npm install
- ` Baixar npm pasta main ` npm install
- ` Baixar npm pasta cypress ` npm install cypress / npm i eslint-plugin-cypress

Abrir **Terminal** e digite abaixo:
- ` Executar dentro pasta API ` npm start-api
- ` Executar dentro main ` npm start
    Irá abrir http://localhost:3000
- ` Executar dentro cypress para criar configuração` npx cypress open
    Vá até o arquivo **.eslintrc** na pasta raíz do projeto e dentro de **extends**, logo acima do plugin do prettier, adicione mais um plugin nessa lista.
    "plugin:cypress/recommended"

Abrir **Terminal** e digite abaixo o teste automação:
- ` Executar  geral ` npx cypress run
- ` Executar  especifico ` npx cypress run --spec "caminho-do-arquivo-do-teste"
- ` Executar browser Edge ` npx cypress run -- browser edge
- ` Executar Mobile ` npx cypress open --config viewportWidth=375,viewportHeight=667