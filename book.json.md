这个是一个标配的book.json文件

```
{
    "title": "gitbook使用指南",
    "author" : "Denny",
    "description" : "关于gitbook客户端关联本地git和本地gitbook服务的使用简介",
    "plugins": [
        "splitter",
        "mermaid",
        "tbfed-pagefooter"
    ],
    "pluginsConfig": {
        "tbfed-pagefooter": {
            "copyright":"",
            "modify_label": "该文件修订时间：",
            "modify_format": "YYYY-MM-DD HH:mm:ss"
        }
    },
    "language" : "zh-hans",
    "links" : {
    "sidebar" : {
        "Custom link name" : "http://blog.webkong.cn",
        "Home" : "http://blog.webkong.cn"
        }
    },
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