# PM86

# ci-test
> KEYMETRICS_NODE=127.0.0.1 KEYMETRICS_PORT=8000 REMOTE_REVERSE_PORT=43554  pm86 interact 07be1dca1e84ce57 09c12de337ec42c4

> pm86-ci 是命令行工具 代替 pm2
> pm86-service 是服务端, 负责 websocket 和 tcp 端口相关
> pm86-cloud 后端 api 界面相关


## Build Setup

**Requires Node.js 6+**

``` bash
# install dependencies
npm install # or yarn

# serve in dev mode, with hot reload at localhost:8080
npm run dev

# build for production
npm run build

# serve in production mode
npm start
```
