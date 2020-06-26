> 在index.html 中script相同位置添加以下

``` html
<script>
    window.$docsify = {
        loadSidebar: true,
        name: '',
        repo: '',
        search: {
            maxAge: 86400000, // 过期时间，单位毫秒，默认一天
            paths: [], // or 'auto'
            placeholder: 'Type to search',

            // 支持本地化
            placeholder: {
                '/zh-cn/': '搜索',
                '/': 'Type to search'
            },

            noData: 'No Results!',

            // 支持本地化
            noData: {
                '/zh-cn/': '找不到结果',
                '/': 'No Results'
            },
            // 搜索标题的最大程级, 1 - 6
            depth: 2
        }
    }
</script>

<script src="//unpkg.com/docsify/lib/plugins/search.js"></script>
```
