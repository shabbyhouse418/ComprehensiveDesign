# ComprehensiveDesign
ComprehensiveDesign 3
综合设计主仓库


项目管理 [https://github.com/shabbyhouse418/ComprehensiveDesign/projects/1](https://github.com/shabbyhouse418/ComprehensiveDesign/projects/1)

无需在这里直接提交代码，建议不要。

# 第一次拉取

## 克隆此项目

```bash
git clone git@github.com:shabbyhouse418/ComprehensiveDesign.git --recursive
```

## 更新子模块

```bash
git submodule foreach git pull origin master
```

## 添加子模块(submodule)

```bash
git submodule add <仓库名>
```
eg git submodule add git@github.com:ka1i/jobsSpider.git



# 拉取[远程仓库](https://github.com/shabbyhouse418/ComprehensiveDesign)

````bash
git pull
git submodule update --init --recursive
git submodule foreach git pull origin master
````

# 提交本地代码
```bash
git add --all
git commit -m "some commit info" ## 填写自己的commit信息。
git push
```

