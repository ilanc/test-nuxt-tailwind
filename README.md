# notes

Translated a vue3 app to nuxt to experiment with layouts and routing. See [layout](./layouts/default.vue).

NB uses hardcoded html in `<template>` - see [4-tw](../4-tw/layouts/simpleDarkHeadlessUI.vue) for a layout which uses `v-for`

## links

- [vue3 vue-router version](file:///code/web/vue3/prototype/shell-layout-routing/README.md)
- [4-tw](../4-tw/README.md)
- [tw-notes.md](../tw-notes.md)

## demos

page-request

- if you go to `Blog (page-request)` it uses `<a href>` so will do a page-request
- all other nav items use `<nuxt-link>` so will do ux route switch