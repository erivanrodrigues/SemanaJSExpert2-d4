O que você não sabia sobre Promises em Javascript

#Todos podem ser usados nas ultimas versões 

npm init -y 

npm i mocha@8 OU npm install --save-dev jest

npm i mocha@8 chai@4 nyc@15 sinon@9
npm i mocha chai nyc sinon 

npm i lokijs@1.5 //banco dados em memoria

MOCHA = O Mocha é uma estrutura de teste JavaScript para programas Node.js 

CHAI = E uma biblioteca de asserção BDD / TDD para o nó e o navegador que pode ser perfeitamente emparelhado com qualquer estrutura de teste de javascript. 

LOKIJS = banco dados em memoria 

NYC = Para montar a estrutura do teste SinonJS = E uma das bibliotecas JavaScript mais populares para testes duplos.



"test:dev": "npx mocha -w --exit test/",
    "test": "npx mocha --parallel test/",
    "test:cov": "npx nyc --check-coverage --instrument --reporter=html --reporter=text npm test",
    "start": "node src/"