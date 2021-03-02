# Pachamama static web app

This app use serverless framework to deploy simple coming soon [pachamama.travel](https://pachamama.travel) website

## Build
```shell
npm install
npm run build # Create the files in dist/
```

## Deploy with [⚡ Serverless Framework](https://github.com/serverless/serverless)
```shell
sls client deploy 
``` 
or if you use **.env.production**
```shell
NODE_ENV=production sls client deploy
```
