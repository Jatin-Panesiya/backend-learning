<h1>Nodejs With Typescript</h1>

npm init -y <br />
npm install typescript ts-node @types/node --save-dev <br />
npx tsc --init <br />
Create a src directory for your TypeScript files: <br />
Inside the src directory, create an index.ts file: <br />

"scripts": { <br />
"build": "tsc", <br />
"dev": "nodemon --exec ts-node src/index.ts" <br />
},
