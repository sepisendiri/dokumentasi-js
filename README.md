# Dokumentasi langkah-langkah javascript

[Halaman npm](https://www.npmjs.com/)

### init npm

```
npm init -y
```

### edit file package.json

```
"scripts": {
"bot": "node main.js"
},
```

### contoh menginstall modul

```
npm i node-telegram-bot-api
sudo npm i nodemon -g
npx puppeteer browsers install chrome
```

### menjalankan skrip berdasarkan package json

```
npm run bot
```

[Halaman generator expressjs](https://expressjs.com/en/starter/generator.html)

### menjalankan express gemerator

```
npx express --view=ejs
npm install
npm audit fix --force
npm start
```

### menginstall modul mysql dan sequelize

```
npm install mysql2 --save
npm install sequelize sequelize-cli --save
```

### init sequelize (orm)

```
npx sequelize init
```

### embuh

```
npx sequelize migration:create --name create-products-table
```

### sequelize membuat tabel atau menghapus tabel

```
npx sequelize db:migrate
npx sequelize db:migrate:undo ==> rollback
```

### install modul fastest-validator

Note : untuk memvalidasi input fields dari body

```
npm install fastest-validator --save
```
