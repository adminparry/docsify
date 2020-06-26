> 在index.html中添加以下

``` html
<link rel="stylesheet" href="//unpkg.com/gitalk/dist/gitalk.css">
<script src="//unpkg.com/docsify/lib/plugins/gitalk.min.js"></script>
<script src="//unpkg.com/gitalk/dist/gitalk.min.js"></script>
<script>
    const gitalk = new Gitalk({
        clientID: 'Github Application Client ID',
        clientSecret: 'Github Application Client Secret',
        repo: 'Github repo',
        owner: 'Github repo owner',
        admin: ['Github repo collaborators, only these guys can initialize github issues'],
        // facebook-like distraction free mode
        distractionFreeMode: false
    })
</script>
```
