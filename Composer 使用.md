Composer 使用记录
-----------------

### 定义本地加载
>本地调试包文件比较方便
```js
{
    "repositories": [
        {
            "type": "path",
            "url": "文件路径"
        }
    ]
}
```

### 定义加载路径&命名空间已经定义加载文件
```js
{
    "autoload": {
        "psr-4": {
            "App\\": "src/app"
        },
        "files": [
            "src/helpers/helpers.php"
        ]
  },
}
```