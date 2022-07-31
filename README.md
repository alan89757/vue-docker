# docker + vue

## 搭建开发环境
```js
$ vue create vue-docker   // vue-cli初始化项目
$ docker image build -t vue-docker .  // 构建镜像
$ docker container run -p 3000:3000 vue-docker  // 运行容器 
$ docker container run -it node:14.19.1-slim /bin/bash  // 进入容器
```



