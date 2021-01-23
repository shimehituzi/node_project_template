1. `git init`
1. `echo "/node_modules\n/dist" > .gitignore`
1. `yarn init -y`
1. `package.json`
    - `"main": "index.ts"`
    - `"scripts": { "start": "npx tsc && node dist/index.js" }`
1. `yarn add typescript @types/node`
1. `npx tsc --init`
1. `cat tsconfig.json |(\rm tsconfig.json; grep -v '^\s*\/' | grep -v '^\s*$' | sed 's/\/.*$//g' | sed 's/ *$//' > tsconfig.json)`
1. `tsconfig.json`
    - `"compilerOptions":`
        - `"target": "ESNext"`
        - `"outDir": "./dist"`
    - `"include": ["src/**/*"]`
    - `"exclude": ["node_modules"]`
1. `mkdir src && touch src/index.ts`
1. `yarn add --dev eslint @typescript-eslint/eslint-plugin @typescript-eslint/parser eslint-config-prettier eslint-config-standard eslint-plugin-import eslint-plugin-node eslint-plugin-prettier eslint-plugin-promise eslint-plugin-standard prettier`
1. `.eslintrc.json` をコピペ
