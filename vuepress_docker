1. 在Docker中创建名为vuepress的容器，并以后台模式运行
docker run --name vuepress -dit alpine
docker exec -it container_id sh

2. 进入容器并安装必要的依赖项
apk add yarn npm nano git

3. 在vuepress目录中初始化VuePress项目，并添加相应的依赖项
mkdir vuepress && cd vuepress
git init
npm init -y
yarn add -D vuepress@next

4. 将VuePress开发和构建脚本添加到package.json文件中
  "scripts": {
    "docs:dev": "vuepress dev docs",
    "docs:build": "vuepress build docs"
  }

6. 创建一个README.md文件作为VuePress文档的入口点
mkdir docs && echo '# Hello VuePress' > docs/README.md

7. 启动VuePress开发服务器
nohup yarn docs:dev > nohup.out &
