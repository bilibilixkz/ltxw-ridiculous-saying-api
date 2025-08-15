# ltxw-ridiculous-saying-api
QQ 群岚天小窝内所有的怪话集锦，自2025.8.15开始收录，接受群内任何人提交

若不不希望自己的话被收录，请直接提交 Pull Request 删掉相关记录，我们将在第一时间合并，并提前在此对任何潜在的冒犯致歉。

## 提交格式
发言应存储在 sayings 文件夹以发言人 QQ 号命名的 TOML 文件内

以下为一个实例
``` toml
name: "Example-Name"
uid: 12345678
sayings: [
    "Speech #1",
    "Speech #2",
    "Speech #3",
]
```
注：TOML 允许数组最后一个值后出现逗号（官方文档中称为“尾逗号”或 "trailing comma"），为方便手机用户提交怪话，请尽量在编辑时保留尾逗号。