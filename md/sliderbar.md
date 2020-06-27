# 添加左侧菜单


在根目录下创建一个_sidebar.md文件 文件名就规定为这个 写错不生效

> index.html添加配置
``` html

 window.$docsify = {
     <!-- 添加这个 -->
    loadSidebar: true,
    name: '',
    repo: ''
}
```

> _slidebar.md文件格式]

这个格式熟悉gitbook的跟summary是一样的格式

``` md
* [summary](/)
* [添加左侧菜单](./md/sliderbar.md)

```

