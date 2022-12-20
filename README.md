# ts-empty
Empty ts project

How to create ts project from scratch ?
>	npm init    // creates package.json
>	npx tsc  --init    // create ts project from scratch
>	npm install –-save-dev typescript     // all the ts libraries needs to be in dev
>	npm install –-save-dev  @types/node   // installs all types 
>	npm install –-save-dev ts-node        // install it globally

create file index.ts  with console.log('Hello World!');
In tsconfig.json
outDir : "./build"   
esModuleInterop: true
target: es2016 
module: commonjs

>	npx tsc     // turns the ts files to js
>	ts-node  index.ts    // executes the ts file

