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
If the route with the web component it, http://localhost:3000/wc, is the inital route, you will see the error in the console. If you browse to the route after initial load from another route, you will not see the error. However, every time you browse back to the route you will see the error again.


### src
The issue only seems to happen with Svelte-produced web components. The source for the web component used here is included in the /hello-web-component folder in case I did something wrong there. (I did also find the issue with web components I found from other Svelte developers.)


