## custom-cra

    1) install  customize-cra react-app-rewired
    2) Create a config-overrides.js file in the root directory
    3) 'Flip' the existing calls to react-scripts in npm scripts for start, build and test

## babel-pugin....

    babel-plugin-module-resolver github

    1) npm install --save-dev babel-plugin-module-resolver
    2) Specify the plugin in your .babelrc with the custom root or alias. Here's an example:
    3) Editors autocompletion

## custom-cra babel

## Prettier

-   .prettierrc
    {
    "arrowParens": "always",
    "bracketSameLine": false,
    "bracketSpacing": true,
    "embeddedLanguageFormatting": "auto",
    "htmlWhitespaceSensitivity": "css",
    "insertPragma": false,
    "jsxSingleQuote": false,
    "printWidth": 120,
    "proseWrap": "preserve",
    "quoteProps": "as-needed",
    "requirePragma": false,
    "semi": true,
    "singleQuote": true,
    "tabWidth": 4,
    "trailingComma": "all",
    "useTabs": false,
    "vueIndentScriptAndStyle": false
    }
-   .vscode/settings.json
    {
    "editor.formatOnSave": true,
    "editor.defaultFormatter": "esbenp.prettier-vscode"
    }

## config SASS

    npm i -D sass
    rest css noma: npm install --save normalize.css
