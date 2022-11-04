# @pnxdxt/prettier-config

## Installation

### Install the package

```
npm i -D @pnxdxt/prettier-config
```

## Setup

1. Create the following file `.prettierrc.js`

   ```javascript
   module.exports = require("@pnxdxt/prettier-config");
   ```

2. Add the following to `scripts` in `package.json`

   ```
   "prettier": "prettier '**/*.{js,ts,json,css,scss,html,hbs,md}' --write"
   ```

3. Install the relevant Editor Addon/Plugin and enable "Prettier on Save".

## Running

```
npm run prettier
```

## Related repos

- https://github.com/pnxdxt/eslint-config
