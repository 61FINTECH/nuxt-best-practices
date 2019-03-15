# Nuxt.js best practices in [61 Financial News](https://news.61Financial.com.au)

## Foreword

As Nuxt.js's [homepage](https://nuxtjs.org) says:

> With Nuxt.js, your application will be optimized out of the box. We do our best to build performant applications by utilizing Vue.js and Node.js **best practices**. To squeeze every unnecessary bit out of your app Nuxt includes a bundle analyzer and lots of opportunities to fine-tune your app.

Which means Nuxt.js was born with best practices and well-tuned performance.

However, this doesn't mean you don't need any best practices or tips when using it. On the contrary, if you are proficient in optimization and always keep best practices in mind, you could build a more stunning SSR app with it.

The *best practices* mentioned above is not only in the realm of Nuxt.js, but also in Vue.js / JS & Node.js / CSS / Nginx / Cache (client & server) / Lazy loading / Transferred size / Security / SEO / UX / etc. The topic is too huge to elaborate here. That's why we always need to keep learning, absorbing the experience of others so that we could always be standing on the shoulders of giants. (By the way, don't forget to share your experience)

Make good use of Google could help you climb up speedily. For example, search `nuxt best practices` and you will get these great articles:

* https://medium.com/vue-mastery/best-practices-for-nuxt-js-seo-32399c49b2e5
* https://vuejsdevelopers.com/2018/07/16/7-tips-large-nuxt-app-vue

The following content might not repeat their tips. Maybe you should find some time to check them out.

## Best practices & Tips

### Self-contained directory structure
According to  [Vue.js Style Guide · Tightly coupled component names](https://vuejs.org/v2/style-guide/#Tightly-coupled-component-names-strongly-recommended):

```

```



### Avoid using a nuxt module if you'd like to use it everywhere

Let's take [axios-module](https://github.com/nuxt-community/axios-module) as an example.



### Update / Upgrade Nuxt.js to a newer version

