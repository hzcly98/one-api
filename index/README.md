# 首页 API 说明文档

#### 获取前十天的图文id集合数组

[http://v3.wufazhuce.com:8000/api/onelist/idlist](http://v3.wufazhuce.com:8000/api/onelist/idlist)

返回结果：

```js
{
  res: 0,
  data: [
    "4252",
    "4242",
    "4241",
    "4065",
    "4145",
    "4231",
    "4240",
    "4219",
    "4216",
    "4215"
  ]
}
```

**Tips:** `data` 数组中的第一项是今天的图文id，最后一项是10天前的图文id。

#### 根据id获取某一天的图文数组集合

```bash
# 其中 `{id}` 替换成当前id值
http://v3.wufazhuce.com:8000/api/onelist/{id}/0
```

Example: 

[http://v3.wufazhuce.com:8000/api/onelist/4215/0](http://v3.wufazhuce.com:8000/api/onelist/4215/0)