# uu-cli


一个快速构建项目的脚手架。  [github地址](https://github.com/xu455255849/vue-xu)


## 项目结构


```javascript
.
├── README.md         //说明文档
├── package.json      //配置信息
└── index.js          //主程序
```
##package说明

```dependencies说明
"dependencies": {
    "chalk": "^2.4.1",                 //终端字符串显示颜色
    "commander": "^2.15.1",            //node 命令行
    "download-git-repo": "^1.0.2",     //下载仓库
    "handlebars": "^4.0.11",           //创建语义化模板
    "inquirer": "^6.0.0",              //命令交互
    "log-symbols": "^2.2.0",           //打印终端调试信息
    "ora": "^2.1.0"                    //终端加载状态
  }
```

## Install 
  
```javascript

  $ npm i uu-cli -g

```

## Usage

uu init [type] [name]

type 为你需要使用的模板

name为你需要创建的项目名
   
目前支持的type：
   
   * pc_bp  PC后台管理系统型项目
   * pc_stat PC后台数据中心系统型项目（准备中）
   * phone_wx 移动端微信应用型项目（准备中）
   * phone 移动端通用型项目（准备中）

   
