# Casa do Código
### Node.js Parte 1: Inovando com JavaScript no backend

```
npm init
npm install express@4.16.3 --save-exact
npm install nodemon@1.18.4 --save-dev --save-exact
npm install -g nodemon@1.18.4 --save-exact
npm install marko@4.13.4-1 --save-exact
npm install sqlite3 --save
npm install body-parser@1.18.3 --save-exact
npm install method-override
```

```
{
  "scripts": {
    "start": "nodemon server.js --ignore *.marko.js"
  }
}
```

### Node.js Parte 2: MVC, autenticação e autorização

```
npm install --save express-validator@5.3.1 --save-exact
npm install uuid@3.3.2 express-session@1.15.6 passport@0.4.0 passport-local@1.0.0 --save-exact
```