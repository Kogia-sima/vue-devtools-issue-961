# vue-devtools-issue-961

Repository for https://github.com/vuejs/vue-devtools/issues/961

## Steps to reproduce

1. Clone this repository

```console
$ git clone https://github.com/Kogia-sima/vue-devtools-issue-961 && cd vue-devtools-issue-961
```

1. Install dependent packages

```console
$ yarn install
```

2. Launch the development server

```console
$ yarn run serve
```

3. Open `http://localhost:8080` in your browser

4. Open Developper tool panel, then select the Vue devtools tab.

5. Now edit `src/App.vue`, then save it.

6. Changes applied once, but no more changes will be applied until reload the page.
