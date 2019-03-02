这个是一个标配的book.json文件

```js
{
    "title": "book",
    "author": "webkong",
    "description": "",
    "plugins": [
        "-lunr", 
        "-search",
        "search-pro",
        "splitter",
        "local-pagefooter",
        "anchor-navigation-ex"
    ],
    "pluginsConfig": {
        "local-pagefooter": {
            "copyright": "webkong",
            "modify_label": "修订时间：",
            "modify_format": "YYYY-MM-DD HH:mm",
            "islocal": true
        },
        "anchor-navigation-ex": {
            "showLevel": true,
            "associatedWithSummary":true,
            "multipleH1":false
        }
    },
    "language": "zh-hans",
    "pdf": {
        "pageNumbers": true,
        "fontSize": 12,
        "paperSize": "a4",
        "margin": {
            "right": 62,
            "left": 62,
            "top": 36,
            "bottom": 36
        }
    }
}
```



