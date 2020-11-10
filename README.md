# vue-codesandbox
vue-codesandbox lets you embed your codesandbox code on to your vue application

## Package setup
install vue-codesandbox by running the following command
```
npm i vue-codesandbox
```
## Usage
In your component, after intalling the package, import it as follows
```
import vuecodesandbox from "vue-codesandbox";
```
Then include the component in your export

```
export default {
  name: "App",
  components: {
    vuecodesandbox,
  },
};
```
Once done, you can now use the component in your templete section with the required props passed in as such

```
<vuecodesandbox 
codeUrl="https://codesandbox.io/s/vue-vue?autoresize=1&fontsize=14&hidenavigation=1&theme=dark" 
width="1000" 
height="1000"
/>
```

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
- **codeUrl(required)** : Type(String) - _This is the link to your codesandbox code you want to embed, you just pass it as prop_
- **width(required)** : Type(Number) - _This is the width your codesandbox will occupy_
- **height(required)** : Type(Number) - _This is the height your codesandbox will occupy_
