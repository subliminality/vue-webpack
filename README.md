# vue-webpack

> A Vue.js project

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).


## Project Lessons

I found two ways to get a Vue project started:

Using the Vue CLI to generate a new project with the command.

``` bash
vue create hello-world
```

However this command didn't set the project up with webpack

The other command I found was

``` bash
vue init webpack my-project
```

which uses a webpack boiler plate and vue-loader for Single=File Components.
