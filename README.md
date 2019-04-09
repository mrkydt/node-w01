# Install Node
1. Download
https://nodejs.org/en/download/
2. Install
3. Check
```
node -v
```
4. check npm command
```
npm -v
```
# Install yarn
1. Install by download from yarn
https://yarnpkg.com/en/
2. Install by npm
```
npm i -g yarn
```
3. check
```
yarn -v
```
# Install Visual studio code
1. Download & install
https://code.visualstudio.com/
2. run
# npm config
```
npm config list -l
```
# yarn config
```
yarn config list
```
# Start a node application
## npm
1. npm init
```
npm init
```
2. Install module
```
npm install [package name]
```
ex: 
```
npm install is-number-prime
```

## yarn
1. yarn init
```
yarn init
```
2. Install module
```
yarn add [package name]
```
ex:
```
yarn add axios
```

# npm & yarn config
## npm config
1. List all config
```
npm config list -l
```
2. Change config by command
```
npm config set [config key] [value]
```
3. Change config by .npmrc (recommend)
https://docs.npmjs.com/files/npmrc

## yarn config
1. List all config
```
npm config list
```
2. yarn config by command
```
yarn config set [key] [value]
```
3. yarn config by .yarnrc
https://yarnpkg.com/lang/en/docs/yarnrc/
