# v-fire

> CRUD with Vue and Firebase
> Deve ser criado o firebase.js na raiz
> Ex: 

import { initializeApp } from 'firebase';

const app = initializeApp({
    apiKey: "xxxx",
    authDomain: "xxx",
    databaseURL: "xx",
    projectId: "xxx",
    storageBucket: "",
    messagingSenderId: "xxx"
});

export const db = app.database();
export const namesRef = db.ref('names');

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build
```

For detailed explanation on how things work, consult the [docs for vue-loader](http://vuejs.github.io/vue-loader).
