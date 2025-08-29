npm install -g less
npm init
npm install --save-dev less
npm run less
npm i -g less-watch-compiler
npm i --save-dev less-watch-compiler

scripts -> json
	"less": "lessc ./src/styles/main.less ./build/styles/main.css",
	"less": "less-watch-compiler ./src/styles ./build/styles",
	"less": "less-watch-compiler ./src/styles ./build/styles main.less",

npm run less
	