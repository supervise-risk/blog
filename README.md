### Hexo 搭建个人博客

#### 安装全局环境

    npm install hexo-cli -g

#### 初始化项目

    hexo init project && cd project

#### 安装项目环境

    npm install

#### 启动

    hexo server

#### 新建页面

    hexo new [layout] <title>

#### 生成静态文件

    hexo generate

完成后部署

#### 部署

    hexo deploy

#### 目录结构

> 具体 blog 写在 source 下

    .
    ├── README.md
    ├── _config.yml
    ├── db.json
    ├── node_modules
    ├── package.json
    ├── public
    ├── scaffolds
    ├── source  # 具体 blog
    └── themes
