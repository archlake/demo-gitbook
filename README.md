# Demo GitBook

- 仓库地址: https://github.com/archlake/demo-gitbook
- 文档地址: https://gitbook.demo.archlake.net/

## 1. 主要功能

- 支持中文和英文全文搜索; 
- Support full text search for zh-Hans and english.

## 2. 使用说明
### 2.1 构建

- travis-ci
- gitlab-ci
- local build

#### 2.1.1. Travis CI

见 [.travis.yml](https://github.com/archlake/demo-gitbook/blob/main/.travis.yml)

#### 2.1.2. Gitlab CI

见 [.gitlab-ci.yml](https://github.com/archlake/demo-gitbook/blob/main/.gitlab-ci.yml)

#### 2.1.3. local build 

```
npm install gitbook-cli -g 
npm install -g gitbook-summary 
gitbook fetch 3.2.3
gitbook install 
book sm
gitbook build .
```

### 2.2. 插件使用说明

#### 2.2.1. gitbook-plugin-anchor-navigation-ex

- [参考链接](https://github.com/zq99299/gitbook-plugin-anchor-navigation-ex)
- 在页面中增加`<!-- ex_nolevel -->`不会在该页面生成层级序号 V1.0.12+

## 3. 参考资料

- gitbook示例, 
  - https://gitbook.zhangjikai.com/
    - https://gitbook.zhangjikai.com/plugins.html
    - https://github.com/zhangjikai/gitbook-use/
  - https://zq99299.gitbooks.io/gitbook-guide
- 常用插件列表: 
  - https://gitbook.zhangjikai.com/plugins.html
  - https://zq99299.gitbooks.io/gitbook-guide/content/chapter/plugin.html


<!-- ex_nolevel -->