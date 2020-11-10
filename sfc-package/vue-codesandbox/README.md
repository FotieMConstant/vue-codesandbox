# vue-codesandbox
vue-codesandbox lets you embed your codesandbox link on to your vue application

## Project setup
```
npm i vue-codesandbox
```
## Usage
```
<template>
  <div id="app">
    <vue-codesandbox
      codeUrl="https://codesandbox.io/s/vue-vue?autoresize=1&fontsize=14&hidenavigation=1&theme=dark"
      width="1000"
      height="1000"
    />
  </div>
</template>

```

## props
codeUrl(required) : String
Width(required) : Type(Number)
height(required) : Type(Number)
