# Blog_Web

## Create node.js

```bash
npm init
```

## Tutorial web: express.js

```bash
npm install express
```

## Install nodemon

```bash
npm install i nodemon --save-dev
```

## Vào package.json => mục script, thêm vào:

```bash
"start": "nodemon index.js"
or nodemon --inspect index.js
```

(dùng để debug)

## install morgan (dùng để nhìn log của web)

ADD:

```bash
npm install morgan
const morgan = require('morgan')
app.use(morgan('combined'))
```
