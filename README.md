# mild-cradle

DevOps engineer · Shell and awk

折腾中的小玩具

## 用法

```bash
cat data.txt | python main.py
```

输出：

```
   3  error: timeout
   1  warn: retry
---
2 unique / 4 lines
```

## 为什么写

现有的工具都太重，就想要个能管道拼接的小东西。

## 待办

- [ ] 支持从文件参数读入
- [ ] 加个输出格式选项
- [ ] 补点测试

## 安装

```bash
git clone https://github.com/USER/mild-cradle.git
cd mild-cradle
pip install -r requirements.txt
```

## License

MIT
