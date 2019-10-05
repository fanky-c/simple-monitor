# simple-monitor
线上环境source-map定位错误


## 使用

模拟部署
```bash
cd client
npm run deploy
```

打开服务器
```bash
cd server
node app
```

打开 CDN 服务器

```bash
cd cdn-server
node app
```

打开监控系统
```bash
cd monitor-server
node app
```

浏览器打开页面 [http://localhost:8000](http://localhost:8000)