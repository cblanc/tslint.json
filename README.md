[![CircleCI](https://circleci.com/gh/cblanc/tslint.json.svg?style=svg)](https://circleci.com/gh/cblanc/tslint.json)

# TSLint Config

## Usage

```bash
npm install --save-dev @cablanchard/tslint
```

In `tslint.json`

```json
{
  "extends": "@cablanchard/tslint"
}
```

In `package.json`

```json
{
  "scripts": {
    "lint": "./node_modules/.bin/tslint --project tsconfig.json -c tslint.json"
  }
}
```

## Licence

MIT

