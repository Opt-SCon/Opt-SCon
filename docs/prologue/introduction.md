- 12321
- 1231231

```html
<!DOCTYPE html>
<html lang="zh-CN">
  <head>
    <meta charset="UTF-8" />
    <title>HUHST ACM | HUHST CAS</title>
    <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1" />
    <meta name="description" content="湖南人文科技学院CAS协会" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link
      rel="stylesheet"
      href="//cdn.jsdelivr.net/npm/docsify@4/lib/themes/vue.css"
    />
  </head>

  <body>
    <div id="app">加载中...</div>
    <div id="disqus_thread"></div>
    <script>
        window.$docsify = {
          name: 'CAS协会官网',
          //repo: 'https://github.com/opt-scon/opt-scon',
          coverpage: true,
          loadSidebar: true,
          loadNavbar: true,
          mergeNavbar: true,

          // 搜索配置
          search: 'auto',
          search: [
            '/', // => /README.md
            '/en/', // => /en/README.md
          ],
          search: {
            maxAge: 86400000, // 过期时间，单位毫秒，默认一天
            paths: [], // or 'auto'
            placeholder: 'Type to search',

            // 支持本地化
            placeholder: {
              '/': '搜索',
              '/en/': 'Search',
            },
            noData: {
              '/': '找不到结果',
              '/en/': 'No Results',
            },

            // 搜索标题的最大层级, 1 - 6
            depth: 2,

            hideOtherSidebarContent: false, // 是否隐藏其他侧边栏内容

            // 避免搜索索引冲突
            // 同一域下的多个网站之间
            namespace: 'website-1',

            // 使用不同的索引作为路径前缀（namespaces）
            // 注意：仅适用于 paths: 'auto' 模式
            //
            // 初始化索引时，我们从侧边栏查找第一个路径
            // 如果它与列表中的前缀匹配，我们将切换到相应的索引
            pathNamespaces: ['/en'],

            // 您可以提供一个正则表达式来匹配前缀。在这种情况下，
            // 匹配到的字符串将被用来识别索引
            pathNamespaces: [/\/(en|zh-CN)\//],
          },

          // 分页导航
          pagination: {
            previousText: {
              '/en/': 'Previous',
              '/': '上一章',
            },
            nextText: {
              '/en/': 'Next',
              '/': '下一章',
            },
            crossChapter: true,
          },

          // 字数统计
          count: {
            countable: true,
            fontsize: '0.9em',
            color: 'rgb(90, 90, 90)',
            language: 'chinese',
            isExpected: false,
          },

          // 代码复制
          copyCode: {
            buttonText: {
              '/en/': 'Copy code',
              '/': '复制代码',
            },
            errorText: {
              '/en/': 'Error',
              '/': '错误',
            },
            successText: {
              '/en/': 'Copied',
              '/': '复制成功',
            },


          //标签页
          tabs: {
            persist: true,
            sync: true,
            theme: 'classic',
            tabComments: true,
            tabHeadings: true,
          },
        };
      >
      <!-- Docsify v4 -->
      <script src="//cdn.jsdelivr.net/npm/docsify@4">
    </script>
    <script src="//cdn.jsdelivr.net/npm/docsify/lib/plugins/search.min.js"></script>
    <script src="//polyfill.io/v3/polyfill.min.js?features=String.prototype.normalize"></script>
    <script src="//cdn.jsdelivr.net/npm/docsify/lib/plugins/zoom-image.min.js"></script>
    <script src="//cdn.jsdelivr.net/npm/docsify-copy-code/dist/docsify-copy-code.min.js"></script>
    <script src="//cdn.jsdelivr.net/npm/docsify-pagination/dist/docsify-pagination.min.js"></script>
    <script src="//unpkg.com/docsify-count/dist/countable.js"></script>
    <script src="//cdn.jsdelivr.net/npm/docsify/lib/plugins/disqus.min.js"></script>
  </body>
</html>
```
