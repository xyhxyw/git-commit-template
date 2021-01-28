# git commit message template
commit 规范如下：[开发中的你的Git提交规范吗？](https://segmentfault.com/a/1190000039056198)
```js
# type为commit类型，scope可选，指哪个模块。description为对commit的简介描述
<type>[scope]: <description>
# 空行
[optional body]
    commit的详细内容
# 空行
[optional footer]
    通常是bug的链接, 比如：
    # issuses关键字，表示关联了哪些issuse
    issues  #1,#2
    # Closes关键字，表示会关闭这些issuse
    Closes  #2 
```

一个完整的commit格式为；

```
feat(Component): 修复了组件的bug

    - 修复了Component的某个bug(一般建议在一行内处理完成)

    issues  #5, #6, #7

    Closes  #7
```