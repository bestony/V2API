#用户相关API 

## 显示用户信息
获取某个用户的信息
```
/api/members/show.json
```
支持参数
```
?username=Livid
?id=1
```
输出结果
```
{
"status": "found",
"id": 1,
"url": "http://www.v2ex.com/member/Livid",
"username": "Livid",
"website": "",
"twitter": "",
"psn": "",
"github": "",
"btc": "",
"location": "91789",
"tagline": "Gravitated and spellbound",
"bio": "I’ve managed to make something I could call my own world, over time, little by little. And when I’m inside it, I feel kind of relieved.",
"avatar_mini": "//cdn.v2ex.co/avatar/c4ca/4238/1_mini.png?m=1466415272",
"avatar_normal": "//cdn.v2ex.co/avatar/c4ca/4238/1_normal.png?m=1466415272",
"avatar_large": "//cdn.v2ex.co/avatar/c4ca/4238/1_large.png?m=1466415272",
"created": 1272203146
}
```
