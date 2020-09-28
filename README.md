# 这是test分支
<p style="background:#008080;">git init</p>
<p style="background:#008080;">git add README.md</p>
<p style="background:#008080;">git commit -m "first commit"</p>
<p style="background:#008080;">git branch -M master</p>
<p style="background:#008080;">git remote add origin https://github.com/yeungxsheng/TEST_Git.git</p>
<p style="background:#008080;">git push -u origin master</p>

### 执行git cz进入interactive模式，根据提示依次填写
```

1.Select the type of change that you 're committing 选择改动类型 (<type>)

2.What is the scope of this change (e.g. component or file name)? 填写改动范围 (<scope>)

3.Write a short, imperative tense deion of the change: 写一个精简的描述 (<subject>)

4.Provide a longer deion of the change: (press enter to skip) 对于改动写一段长描述 (<body>)

5.Are there any breaking changes? (y/n) 是破坏性修改吗？默认n (<footer>)

6.Does this change affect any openreve issues? (y/n) 改动修复了哪个问题？默认n (<footer>)
```

### 生成的commit message格式如下：

```
<type>(<scope>): <subject>

<BLANK LINE>

<body>

<BLANK LINE>

<footer>
```