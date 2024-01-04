## 博客


## 安装软件


```bash

  brew install git

  brew install hugo
  
  brew install go 
  
```

## 常用命令


##  内容管理


```bash
# 创建新新博客
    hugo new blog/my-first-post.md

# 创建新网页
    hugo new page/about.md

```

+ 本地启动
````bash
hugo server -D
````

+ 编译 
```bash
 env HUGO_ENV="production" hugo -d \docs
```

+ 上传部署
```bash
  git add -A &&  git commit -m "提交内容注释" && git push
```