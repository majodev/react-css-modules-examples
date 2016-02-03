# React CSS Modules Examples


Issue fixed by v3.7.4, see [#89](https://github.com/gajus/react-css-modules/issues/89).

---

**Issue Fork!** Example code to reproduce an issue with Safari + react-css-modules < v3.7.0.

Updated components don't no receive their [local styles](doc/fail_in_safari.png) (however they do if [dev-tool are open](doc/works_with_devtools_open.png)).

---

https://github.com/gajus/react-css-modules

## Setup

```sh
git clone https://github.com/gajus/react-css-modules-examples.git
cd ./react-css-modules-examples
npm install
```

## Running webpack-dev-server Using React Hot Loader

```sh
node ./node_modules/.bin/webpack-dev-server
```

## Using React Hot Loader and BrowserSync

```sh
node ./server.js
```
