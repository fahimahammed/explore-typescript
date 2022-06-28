# Getting Started
- It is a superset of the JavaScript language.
- It is an object oriented programming language.
- It developed by Microsoft Corporation.


## How to set up a typescript project.
Install Node and the TypeScript Compiler.
- Download and run the .msi installer for ``Node``.
- Then install TypeScript compiler globally on your machine by running the following command:
```bash
npm i -g typescript
```

To check the installation successfull, run the following command:
```bash
tsc -v
```


## How to compile TypeScript code
At first, open VS code or any text editor and create a typescript file ( e.g. script.ts ).
Then write some TypeScript code:

```bash
const word = "Hello World!";
console.log(word);
```

To compile the typescript code, run the following command:
```bash
tsc script.ts
```

TypeScript compiler will compile the typescript code into JavaScript.



## How to set up TypeScript config file
At first, we need to create a config file. To create a config file, we need to run the following command:
```bash
tsc --init
```

To config your tsconfig file, Please follow this link: https://www.typescriptlang.org/docs/handbook/tsconfig-json.html


