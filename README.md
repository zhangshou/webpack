## 1. 创建app目录并创建入口文件
## 2. 创建webpack.config.js文件，指定入口文件和输出的目录和文件名 
## 3. 初始化package.json文件 
```
npm init -y
```
## 4. 添加脚本
```
"scripts": {
    "build": "webpack"
  }
```
## 5. 运行脚本
```
npm run build
```
## 6. 运行脚本的时候会去找 当前目录下的node_modules/.bin/webpack.cmd 文件并执行，执行的时候会读取webpack.config.js文件并进行打包入口文件，然后保存到目标目录指定文件名中
