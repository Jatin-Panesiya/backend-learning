<h1>Nodejs With Typescript</h1>

npm init -y
npm install typescript ts-node @types/node --save-dev
npx tsc --init
Create a src directory for your TypeScript files:
Inside the src directory, create an index.ts file:

"scripts": {
"build": "tsc",
"dev": "nodemon --exec ts-node src/index.ts"
},
