No prompt

npm init
npm install -g typescript
tsc –init
----------------------------------------------------------------------------------------------------------------
No arquivo tsconfig.json
habilitar Module, rootDir (./src),
habilitar outdir (./dist)
----------------------------------------------------------------------------------------------------------------
No prompt

npm install –save-dev @types/node
npm install -g nodemon
nodemon src/index.ts
------------------------------------------------------------------------------------------------------------------------------------------
criar index.ts
------------------------------------------------------------------------------------------------------------------------------------------


No package.json
Copiar:
{
  "name": "projetos",
  "version": "1.0.0",
  "description": "",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1",
    "start-dev": "nodemon src/index.ts"
  },
  "author": "",
  "license": "ISC",
  "devDependencies": {
    "@types/node": "^17.0.34",
    "ts-node": "^10.7.0"
  }
}

--------


-------------------------------------------------------------------------------------------------------------------------------------
No package.json

Colocar , no final do “test”,
“nome1 que quer colocar”: nodemon src/index.ts


--------------------------------------------------------------------------------------------------------------------------
No prompt

npm install  -D ts-node
run nome1
