# Node-REPL-Tool
[![travis build](https://api.travis-ci.org/atom2ueki/node-repl-tool.svg?branch=master)](https://travis-ci.org/atom2ueki//node-repl-tool)

A project based auto generated NodeJS REPL tool

## How it looks like
<img src="https://github.com/atom2ueki/node-repl/blob/master/sample.png" width="250">

## Run example
```
cd example

npm install

npm start

```

## How to use / test
- Step1: `npm install node-repl-tool --save-dev`
- Step2: define your .replignore file, just like .gitignore, so node-repl will ignore those path or files
- Step3: init node-repl-tool
```
var repl = require('../src/index');

var project_root_path = __dirname

repl.run(project_root_path)

```

ctrl+c twice or ctrl+d to exit

## Roadmap
- [x] pack it into npm
- [x] re-register solution
- [x] add mocha test cases
- [x] auto register functions
- [x] identify ignore file
- [ ] show functions registered
- [ ] watch file changes

## Testing
```
npm test

```
