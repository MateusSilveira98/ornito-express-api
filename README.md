## Ornito CLI
Command line tool to start a new nodejs API based on express framework with Ornito structure.

## Running

**`Ornito CLI`** allow you to easily start an API and code oriented to modules. strives to be an easily embeddable and beautiful command line interface for [Node.js](https://nodejs.org/) (and perhaps the "CLI [Xanadu](https://en.wikipedia.org/wiki/Citizen_Kane)").

**`Ornito CLI`** needs the following techonologies to be able to start up.
- nodejs > 7.6.0
- postgres
- mongodb (if you're going to use it)
- redis (if you're going to use it)

> **Note:** **`Ornito CLI`** is still in active development, we want to deliver more features like eslint, iugu integration and more.

## Command line
``` shell
npm install -g ornitojs
ornito start
```

### Creating a new module
``` shell
ornito module user
```

### 💡 To do:

* create database if does not exist (node-postgres)
* show eslint options (standard, standard2, airbnb...)
* tests using jest
* create job from CLI
* create module from CLI
* option to inform database settings while creating structure
