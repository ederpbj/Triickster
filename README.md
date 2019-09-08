# Triickster

>Aulas

    https://medium.com/baixada-nerd/criando-um-crud-completo-com-nodejs-express-e-mongodb-parte-1-3-6c8389d7147d
    
git clone https://github.com/ederpbj/Triickster.git

>Iniciando projeto

    npm init 

>Usando express

    npm install express --save

>Start teste

    yarn start
    console.log('A força esta com vc!')

>EJS para parte visual

    npm install ejs --save

>O Nodemon reinicia o servidor automaticamente sempre que você salva um arquivo que o servidor usa

    npm install nodemon --save-dev

/**

Note que estamos usando uma sinalização --save-dev aqui porque estamos usando apenas o Nodemon quando estamos desenvolvendo. Esse sinalizador salva o Nodemon como uma devDependency no nosso arquivo package.json

**/
>Altera script

    "scripts": {
        "test": "echo \"Error: no test specified\" && exit 1",
        "dev": "nodemon server.js"
        //"start": "node server.js"
      },

>Agora, você pode executar o npm run dev para acionar o nodemon server.js

    npm run dev

>Lê dados do Form

    npm install body-parser --save

>O Express nos permite adicionar middleware como body-parser ao nosso aplicativo com o método use

>O método urlencoded dentro de body-parser diz ao body-parser para extrair dados do elemento <form> e adicioná-los à propriedade body no objeto request