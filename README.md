# To test

```
npm install
npm run dev
```

# NOTES

https://nuxtjs.org/guide/routing/

```js
  <nuxt-link to="/">Home page</nuxt-link>
  <nuxt-link :to="{name: }">Home page</nuxt-link>

  this.$route.hash
  this.$route.query
  this.$route.params

  this.$router.push
  this.$router.replace

  const path = this.$router.resolve({
    name: "",
    params: { },
    query: { }
  }).href
```
