基于NodeJs+MongoDB搭建的电影网站
=================
简介
---------------
本项目是通过[慕课网](http://www.google.com) , [node建站攻略](http://www.imooc.com/learn/637) 的教程搭建的，版本为windows node.js v0.10.26

项目结构:
---------------

> ├── app.js            项目入口文件<br />
│<br />
├── app               MVC文件目录<br />
│   ├── controllers   控制器目录<br />
│   │   ├── category.js <br />
│   │   ├── comment.js <br />
│   │   ├── index.js <br />
│   │   ├── movie.js <br />
│   │   └── user.js <br />
│   │ <br />
│   ├── models      模型目录 <br />
│   │   ├── category.js  <br />
│   │   ├── comment.js  <br />
│   │   ├── movie.js  <br />
│   │   └── user <br />
│   │
│   ├── schemas       模式目录 <br />
│   │   ├── category.js  <br />
│   │   ├── comment.js  <br />
│   │   ├── movie.js  <br />
│   │   └── user.js <br />
│   │
│   └── views         视图文件目录 <br />
│       ├── includes <br />
│       └── pages <br />
│
├── config               路由配置文件目录 <br />
│       └── routes.js <br />
│ <br />
├── node_modules      node模块目录（需根据package重新安装） <br />
│ <br />
├── public            静态公共文件目录 <br />
│   ├── js        JS脚本目录 <br />
│   ├── libs      （bower安装bootstrap&jQuery的目录，需安装） <br />
│   └── upload        用户自定义上传图片存储目录 <br />
│ <br />
├── README.md <br />
├── bower.js     静态资源版本 <br />
└── package.json <br />
