# skiresort_information

# やること

## skiresort_information

- Table作成
- tableにテストデータを入力
- ヘッダ（タイトル）
- レコードの実装
- input-formをレコードに反映させる

## input-form

- Form作成


---

## Project setup

最初にプロジェクトフォルダ作る必要なし！！

リポジトリもまだ作らなくて良い！！

- プロジェクト作成する親ディレクトリに移動
    
    ```jsx
    % cd git
    ```
    

- skiresort-informationプロジェクトを作成
    
    ```jsx
    % vue create skiresort-information
    ```
    
    ```jsx
    Vue CLI v5.0.8
    ? Please pick a preset:
      Default ([Vue 3] babel, eslint)
      Default ([Vue 2] babel, eslint)
    > **Manually select features**
    ```
    
    ```jsx
    ? Check the features needed for your project: (Press <space> to select, <a> to toggle all, <i> to invert selection, and <enter> to proceed)
     (*) **Babel**
    >(*) TypeScript
     ( ) Progressive Web App (PWA) Support
     (*) **Router**
     ( ) Vuex
     ( ) CSS Pre-processors
     (*) **Linter / Formatter**
     ( ) Unit Testing
     ( ) E2E Testing
    ```
    
    Vue.jsバージョン2.x
    
    ```jsx
    ? Choose a version of Vue.js that you want to start the project with
      3.x
    > **2.x**
    ```
    
    クラス形式を選択（Enterキー！※デフォルトの**"Y"**）
    
    ```jsx
    ? Use class-style component syntax? (**Y**/n)
    ```
    
    Enterキー！※デフォルトの**"Y”**
    
    ```jsx
    ? Use Babel alongside TypeScript (required for modern mode, auto-detected polyfills, transpiling JSX)? (Y/n)
    ```
    
    ```jsx
    ? Use history mode for router? (Requires proper server setup for index fallback in production) (Y/n)
    ```
    
    ```jsx
    ? Pick a linter / formatter config:
      ESLint with error prevention only
      ESLint + Airbnb config
    > **ESLint + Standard config**
      ESLint + Prettier
    ```
    
    ```jsx
    ? Pick additional lint features: (Press <space> to select, <a> to toggle all, <i> to invert selection, and <enter> to proceed)
    >**(*) Lint on save**
     ( ) Lint and fix on commit
    ```
    
    ```jsx
    ? Where do you prefer placing config for Babel, ESLint, etc.? (Use arrow keys)
    > **In dedicated config files**
      In package.json
    ```
    
    デフォルト：**N**
    
    ```jsx
    ? Save this as a preset for future projects? (y/N)
    ```
    
    ```jsx
    cd skiresort-information
    ```
    

- element-ui導入
    
    カレントディレクトリ：プロジェクトフォルダ（skiresort-information）
    
    ⚠️ルートディレクトリに注意
    
    ```jsx
    % vue add element
    ```
    
    Fully import選択（フルインストール）
    
    ```jsx
    ? How do you want to import Element? (Use arrow keys)
    ❯ Fully import
    Import on demand
    ```
    
    「**ElementのSCSS変数を上書きしますか？**」を「**N(No)**」
    
    ```jsx
    ? Do you wish to overwrite Element's SCSS variables? **N**
    ```
    
    「**ロードするロケール(地域設定)を選択してください**」を「**ja(日本)**」
    
    ```jsx
    ? Choose the locale you want to load
      **ja**
    ```
    
    ```jsx
    % yarn serve
    ```
    
    真ん中にel-buttonがあれば成功🙌

    package json

**"element-ui": "^2.4.5",**　があること確認

## Project setup
```
yarn install
```

### Compiles and hot-reloads for development
```
yarn serve
```

### Compiles and minifies for production
```
yarn build
```

### Lints and fixes files
```
yarn lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
