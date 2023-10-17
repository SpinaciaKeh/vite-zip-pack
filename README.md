# vite-zip-pack
vite插件-将打包结果压缩为zip文件

---

需要安装依赖`jszip`

```
pnpm add jszip
```

---

#### 存在的问题

- 使用`closeBundle`钩子，可能会与其他`async closeBundle`的插件冲突，无法确保压缩在最后一步执行；
- 暂时无法自动将压缩结果复制到剪贴板；

---

_先在这里做个备份，有时间再优化_