
给SPA项目起后端服务的简易Node服务器代码

```
node app.js
```

pm2起服务的话：-n后面是进程名字
```
pm2 start app.js --watch -n node-app-demo
```

备注：项目中的release文件夹是为了示例没放在gitignore，如是正式开发，不要上传git