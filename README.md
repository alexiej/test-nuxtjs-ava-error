# test-02-ava

> My legendary Nuxt.js project

## Build Setup

```bash
# install dependencies
$ yarn install

# serve with hot reload at localhost:3000
$ yarn dev

# build for production and launch server
$ yarn build
$ yarn start

# generate static project
$ yarn generate
```

For detailed explanation on how things work, check out [Nuxt.js docs](https://nuxtjs.org).


## ERROR

```
yarn test
```

output:

```
yarn run v1.22.4
warning ../../../../package.json: No license field
$ ava
TAP version 13
[vue-test-utils]: isVueInstance is deprecated and will be removed in the next major version
# specs › Logo › is a Vue instance
ok 1 - specs › Logo › is a Vue instance
Download the Vue Devtools extension for a better development experience:
https://github.com/vuejs/vue-devtools
# e2e › index › before hook
# Exited because no new tests completed within the last 10000ms of inactivity
not ok 2 - Exited because no new tests completed within the last 10000ms of inactivity

1..2
# tests 2
# pass 1
# fail 2

error Command failed with exit code 1.
info Visit https://yarnpkg.com/en/docs/cli/run for documentation about this command.
```
