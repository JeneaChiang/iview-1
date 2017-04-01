## 介绍
基于 vue-cli 的 Vue js 单页应用项目模板。

## 使用
```bash
# 下载代码
$ git clone https://github.com/zhaotoday/vue.js.git
```

```bash
# 安装依赖
$ npm install
```

```bash
# 开发调试
$ npm run dev
```

```bash
# 构建
$ npm run build
```

```bash
# 执行单元测试
$ npm run unit
```

```bash
# 执行 e2e 测试
$ npm run e2e
```

```bash
# 执行所有测试
$ npm test
```

## 对 vue-cli 模板的一些小修改
#### 将模板文件 index.html 从根目录移至 src 目录，将构建文件 index.html 移至根目录
理由：原 vue-cli 构建后的 index.html 存放在 dist 目录下。但通常，我们需要把整个项目提交到 git/svn，然后部署，这时候访问的默认首页需要是构建后的 index.html。

#### 提供 sass 支持
```bash
$ npm install --save-dev node-sass
$ npm install --save-dev sass-loader
```

#### 配置 postcss autoprefixer
