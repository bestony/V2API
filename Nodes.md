# 节点相关API 

## 展示所有Node
可以输出所有的Node
```
/api/nodes/all.json
```
输出结果
```
[
{
"id": 1,
"name": "babel",
"url": "http://www.v2ex.com/go/babel",
"title": "Project Babel",
"title_alternative": "Project Babel",
"topics": 1118,
"stars": 343,
"header": "Project Babel - 帮助你在云平台上搭建自己的社区",
"footer": "V2EX 基于 Project Babel 驱动。Project Babel 是用 Python 语言写成的，运行于 Google App Engine 云计算平台上的社区软件。Project Babel 当前开发分支 2.5。最新版本可以从 <a href=\"http://github.com/livid/v2ex\" target=\"_blank\">GitHub</a> 获取。",
"created": 1272206882,
"avatar_mini": "//cdn.v2ex.co/navatar/c4ca/4238/1_mini.png?m=1419840368",
"avatar_normal": "//cdn.v2ex.co/navatar/c4ca/4238/1_normal.png?m=1419840368",
"avatar_large": "//cdn.v2ex.co/navatar/c4ca/4238/1_large.png?m=1419840368"
},
...
]
```

## 查看Node 信息
查看具体的Node信息
```
/api/nodes/show.json
```
支持参数
```
?name=YourNodeName
?id=YourNodeId
```
输出结果如下
```
{
"id": 1,
"name": "babel",
"url": "http://www.v2ex.com/go/babel",
"title": "Project Babel",
"title_alternative": "Project Babel",
"topics": 1118,
"stars": 343,
"header": "Project Babel - 帮助你在云平台上搭建自己的社区",
"footer": "V2EX 基于 Project Babel 驱动。Project Babel 是用 Python 语言写成的，运行于 Google App Engine 云计算平台上的社区软件。Project Babel 当前开发分支 2.5。最新版本可以从 <a href=\"http://github.com/livid/v2ex\" target=\"_blank\">GitHub</a> 获取。",
"created": 1272206882,
"avatar_mini": "//cdn.v2ex.co/navatar/c4ca/4238/1_mini.png?m=1419840368",
"avatar_normal": "//cdn.v2ex.co/navatar/c4ca/4238/1_normal.png?m=1419840368",
"avatar_large": "//cdn.v2ex.co/navatar/c4ca/4238/1_large.png?m=1419840368"
}
```
