# Como criar um projeto do Node

npm init -y

# Instalar o Typescript

npm install typescript --save-dev

# Inicializar e Configurar o Typescript

```npx tsc --init```

## Formato do tsconfig.json recomendado:

```{
{
  "compilerOptions": {
    "target": "es2016",
    "module": "commonjs",
    "rootDir": "./src",
    "outDir": "./dist",
    "esModuleInterop": true,
    "forceConsistentCasingInFileNames": true,
    "strict": true,
    "skipLibCheck": true
  }
}
```

## Como compilar o projeto

```npx tsc``` - Transforma typscript -> javascript :

```node ./dist/nome.js``` - roda o código que anteriormente foi passado para javascript.
