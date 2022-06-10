## 关于本站
本站是通过jekyll构建的，使用chirpy主题。

## 使用Chirpy构建的两种方式
1. 通过Chirpy Starter进行构建。
本站即采用此种方式。优点是简单，缺点是不可定制修改。
Chirpy Starter [![Gem Version](https://img.shields.io/gem/v/jekyll-theme-chirpy)](https://rubygems.org/gems/jekyll-theme-chirpy) [![GitHub license](https://img.shields.io/github/license/cotes2020/chirpy-starter.svg?color=blue)][mit]

2. 通过克隆jekyll-theme-chirpy进行构建。
优点是可以定制，缺点是相对复杂。
[jekyll-theme-chirpy](https://github.com/cotes2020/jekyll-theme-chirpy/)


## 本地运行测试
先从github上克隆到本地。然后在本地执行:
1. 安装依赖
```sh
bundle
```

2. 启动服务
```sh
bundle exec jekyll s
# 或者
jekyll server
```
启动成功后，通过http://localhost:4000即可访问。

## 部署到github **这一步非常重要。**
与其他主题略有差别的是chirpy会通过自动构建将静态内容创建到gh-pages分支里面，所以需要通过Settings->Pages->Source，将分支从main切换为gh-pages分支，保存。

