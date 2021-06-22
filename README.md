# PostgreSQL Todo App
#### Ognjen Vukotić 27/18

Ovo je fullstack aplikacija čija je glavna funkcionalnost "Todo List" odnosno lista stvari za uraditi.
Nije realan projekat već je nastao iz edukativnih razloga.

## Features

- PostgreSQL
- NodeJS
- React
- Express

Projekat na backendu koristi PostgreSQL, express i nodejs. Client/Front-end dio je powerovan sa react-om i bootstrapom.


## Tech

Dillinger uses a number of open source projects to work properly:


And of course Dillinger itself is open source with a [public repository][dill]
 on GitHub.

## Setup projekta za lokalno korišćenje
### Instalacija dev dependency-eva
```sh
git clone https://github.com/ognjen-dev/postgrestodo.git
cd server
npm install
cd ..
cd client
npm install
```

### Pokretanje back-end dijela
```sh
cd server // iz iz root foldera
nodemon index.js // kako bi pokrenuli server + live preview koristimo nodemon
```
##### U psql shell-u je potrebno da se login-ujemo sa svojim kredencijalima i otovorimo bazu koju koristimo u ovom slucaju "perntodo"
### Pokretanje client dijela lokalno 
```sh
cd client // iz iz root foldera
yarn start // kako bi pokrenuli live preview
//ili npm start zavisno od toga koji package manager koristimo
```

## Pluginovi

| Plugin | README |
| ------ | ------ |
| Bootstrap |https://getbootstrap.com/docs/4.0/getting-started/introduction/ |
| Nodemon | https://github.com/remy/nodemon |
| Git | https://git-scm.
