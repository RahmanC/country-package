# rhammy-countries

## How to use it?

You can use the hook this way:

### Install
```bash
# with npm
npm install rhammy-countries

# with yarn
yarn add rhammy-countries
```

### Usage

- Import the package in your app:
```js
import {useCountry} from 'rhammy-countries';
```
- Get the country information from the hook:
```js
const {loading, error, country} = useCountry('Nigeria')'
```