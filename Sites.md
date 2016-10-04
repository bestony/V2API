# 站点信息API 

## 展示站点统计信息

可以输出当前的用户数和主题数

```
 /api/site/stats.json
```
输出结果
```
{
"topic_max": 304597,
"member_max": 193376
}
```

## 展示站点信息
输出V站的基础信息
```
/api/site/info.json
```
输出结果
```
{
"title": "V2EX",
"slogan": "way to explore",
"description": "创意工作者们的社区",
"domain": "www.v2ex.com"
}
```
