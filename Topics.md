#主题

##展示最新文章
展示最新文章， 相当于首页的“全部”这个 tab 下的最新内容。
```
/api/topics/latest.json
```

##展示最热文章
相当于首页右侧的 10 大每天的内容。
```
/api/topics/hot.json
```

## 显示主题内容
显示主题内容
```
/api/topics/show.json?id=1
```

## 显示用户的主题
筛选出用户的主题
```
/api/topics/show.json?username=xiqingongzi
```

## 显示节点主题
显示某个节点的主题
```
/api/topics/show.json?node_id=1
/api/topics/show.json?node_name=v2ex
```

## 发布主题
发布主题，此接口需要鉴权，接口判定Header中的`Authorization`来进行身份验证
```
/api/topics/create.json
```
