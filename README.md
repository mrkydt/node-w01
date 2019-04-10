# Contents
- [Install nvm](#)
- [Init a ndode application](#)
- [npm & yarn]()
- [npm & yarn config]()
- [Install visual studio code](#)

# Install nvm
Macos/Linux: https://github.com/creationix/nvm/blob/master/README.md

Windows: https://github.com/coreybutler/nvm-windows
Download: https://github.com/coreybutler/nvm-windows/releases

# Install Node
1. Download
https://nodejs.org/en/download/
2. nvm command
```
nvm install [node version]
```
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
.npmrc
```
registry=https://def.xyz
```

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
.yarnrc
```
registry "https://abc.xyz"
```
# Install Visual studio code
1. Download & install
https://code.visualstudio.com/
