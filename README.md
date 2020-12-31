1. `git iniy`
1. `nvim .gitignore`
1. `yarn init -y`
1. `package.json` の `"main"` を `"index.ts"` にする
1. `yarn add typescript @types/node`
1. `npx tsc --init`
1. `cat tsconfig.json |(\rm tsconfig.json; grep -v '^\s*\/' | grep -v '^\s*$' | sed 's/\/.*$//g' | sed 's/ *$//' > tsconfig.json)`
1. `yarn add eslint @typescript-eslint/eslint-plugin @typescript-eslint/parser prettier eslint-config-prettier eslint-plugin-prettier`
1. [ここの](https://qiita.com/suzuki_sh/items/fe9b60c4f9e1dbc5d903) `.eslintrc.json` をコピペ
1. [ここの](https://qiita.com/mysticatea/items/9da94240f29ea516ae87#セミコロンを省略するスタイル) の `"rules"` を `.eslintrc.json` に追記
1. `mkdir src && touch src/index.ts`
