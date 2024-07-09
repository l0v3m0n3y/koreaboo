# koreaboo
JavaScript library for koreaboo.com
# main
```js
async function main(){
    const {koreaboo} = require('./koreaboo');
    const korea= new koreaboo();
    let req=await korea.search("bts")
    console.log(req["response"]["docs"])
}
main()
```
