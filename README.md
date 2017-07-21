[toc]
# 1. 为知笔记标题自动编号插件
编辑比较长的文档时，标题没有编号，读者很难一眼看清楚整个文档的结构，但是位置笔记的 Markdown 没有这个功能，所以计划编写一个插件为知笔记的 Markdown 自动为标题增加序号。

# 2. 可行性调研
## 2.1 涉及技术点
为知笔记开发文档：http://www.wiz.cn/manual/plugin/index.html

# 3. 功能点
## 3.1 转换
例：
```
# 标题一
## 标题二
### 标题三

# 标题四
```
自动转换为
```
# 1. 标题一
## 1.1 标题二
### 1.1.1 标题三

# 2. 标题四
```

## 3.2 反转
例：
```
# 1. 标题一
## 1.1 标题二
### 1.1.1 标题三

# 2. 标题四
```
自动转换为
```
# 标题一
## 标题二
### 标题三

# 标题四
```

# 详细设计