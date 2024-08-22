# 快速发送你想发送的任何骚话

## 文件解释

### [short_sentences_reset.cfg](./short_sentences_reset.cfg)

恢复你的绑定，请在此修改其中的绑定为你正常使用的绑定。所使用的键位为：`1`,`2`,`3`,`4`,`5`,`6`,`7`,`9`

### [short_sentences1.cfg](./short_sentences1.cfg)

`short_sentences1.cfg`/`short_sentences2.cfg`/`short_sentences3.cfg`文件结构几乎一致，其中

- `echo 1.`为控制台回显提示部分，你可以在此设置一个易于记忆的简单提示词，用于提示按键对应的语句
- `bind 1 "exec short_sentences_reset.cfg;say 1"`为实际控制部分，只需更改`say 1`中`1`的部分为你想要快速发送的语句即可
  
## 使用方法

1. 阅读上述文件解释后按照自己的需求修改配置内容
2. 将[short_sentences_reset.cfg](./short_sentences_reset.cfg)放入DDNet对应数据存储目录下
3. 打开DDnet，F1控制台输入`exec short_sentences_reset.cfg`
4. 按照自己的需求增减[short_sentences1.cfg](./short_sentences1.cfg)的数量并放入DDNet对应数据存储目录下
5. 开始愉快的玩耍吧:P

*增加页数或者减少页数注意*

- `echo " ——页 1/3—— "`可以按需修改
- 列表采用循环翻页设计，需要将头尾两页的`bind 6` `bind 7`更改为对应`cfg`

~~当然也可以图方便直接用[example](./example/)里的~~