# pkg-puppeteer
build puppeteer with zeit/pkg 

```
npm i puppeteer
npm i pkg
 
```
copy chrome bin folder of node_module puppeteer  ```chrome-mac```  or ```win64-555668``` to ./build/chromium
https://github.com/zeit/pkg/issues/204#issuecomment-363219758


```pkg index.js  --out-path ./build```

Spired by https://github.com/zeit/pkg/issues/204#issuecomment-378929002 
