# get-countries-data

## How to use it?

You can use the hook this way:

### Install
```bash
# with npm
npm install get-countries-data

# with yarn
yarn add get-countries-data
```

### Usage

- Import the package in your app:
```js
import {useCountry} from 'get-countries-data';
```
- Get the country information from the hook:
```js
const {loading, error, country} = useCountry('Nigeria')'
```