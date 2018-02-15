## Prerequisites

- NodeJS
- NPM
- Yarn

## Set up

### Install Lerna globally
```
npm i -g lerna
```

### Obtener el repo
```
git clone --recurse-submodules https://github.com/cmartinezdev/lerna-test-gitsubmodules.git
```

### Install project dependencies
```
lerna bootstrap
```

## Run
```
cd packages/run
npm start
```