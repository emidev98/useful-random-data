# Keplr Chains Data

Most of the chains can be imported thru [Ping Pub](https://ping.pub/). In case you cannot import your chain from the previously mentioned site, use [this function](https://github.com/chainapsis/keplr-example/blob/cw-20/src/main.js#L23-L104) from the browser console sending the data from the chain you want to import. Some models can be found in the same folder as this README.

```js
window
    .keplr
    .experimentalSuggestChain({})
    .then(console.log)
    .catch(console.error);
```