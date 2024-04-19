# Codigo Lender Example Generated Code
Build a simple defi lender dApp in under an hour using the Código Platform.

## Build contract

From within the program directory

```shell
cargo build-sbf
```

## Deploy contract

From within the program directory

```shell
solana program deploy target/deploy/informal_lender.so
```

##Modify program_client/app.ts

Replace your program id you got after deploying your program in the string where it says "PASTE_YOUR_PROGRAM_ID_HERE"
![image](https://github.com/darkvallen/codigo-lender-example/assets/117942738/bacfbd79-8eff-4aab-aa18-aeb8393716a2)

## Run Client

From within the program_client directory
```shell
npm install @types/node ts-node
```
after it completes, execute this command :
```shell
npx ts-node app.ts
```

![image](https://github.com/darkvallen/codigo-lender-guide/assets/117942738/b13638c1-8610-4c73-be50-e37430143a94)
