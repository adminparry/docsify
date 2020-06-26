
> 发布到git page

跟gitbook不同的是 docsify使用的是直接使用markdown解析 而不是生成html

所以直接找到index.html的地方直接发布就可以了

``` bash

npm install -g gh-pages

gh-pages -d docs
```

