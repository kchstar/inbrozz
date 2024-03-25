$ npm install eslint

$ touch .eslintrc .js

> package.json
> "script": {
>   "lint": "eslint src"
> }
$ npm run lint 검사 

$ npm install prettier
    $ npx prettier src/**/*
    $ npx prettier src/**/* --write

: eslint-config-prettier와 eslint-plugin-prettier


$ npm install husky
    > package.json
        > "husky":{
            "hooks":{
                "pre-commit": "echo \ "이것은 커밋전에 출력됨\""
            }
        }