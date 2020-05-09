# Producing issue



### Using `degit`

[`degit`](https://github.com/Rich-Harris/degit) is a scaffolding tool that lets you create a directory from a branch in a repository. Use either the `rollup` or `webpack` branch in `sapper-template`:

```bash
# for Rollup
npx degit "bjpohl/sveltesappererror" my-app

```

### Running the project


```bash
cd my-app/with-webcomponent
npm install
npm run dev
```

Open up [localhost:3000/wc](http://localhost:3000/wc). If you browse to [localhost:3000/test](http://localhost:3000/test) the same web component does not throw error in console on static page. The error does not occur if you browse to the page after starting at index. (i.e. the issue seems to be only in SSR'd pages).



### src
The issue only seems to happen with Svelte-produced web components. The source for the web component used here is included in the /hello-web-component folder in case I did something wrong there. (I did also find the issue with web components I found from other Svelte developers.)


