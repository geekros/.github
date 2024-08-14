# chat_desktop

### Environment

> NodeJS 18.13.0~20.14.0、Python 3.10.10、VS2019


### Yarn配置

```shell
yarn config delete proxy
npm config rm proxy
npm config rm https-proxy
```

```shell
npm config set registry https://registry.npmmirror.com
npm config set ELECTRON_MIRROR "https://registry.npmmirror.com/-/binary/electron/"
npm config set "strict-ssl" false -g
yarn config set registry https://registry.npmmirror.com
yarn config set ELECTRON_MIRROR "https://registry.npmmirror.com/-/binary/electron/"
yarn config set "strict-ssl" false -g
```

### Configuration

> 安装VS2019，在S2019中勾选C++桌面开发并安装。

> 安装Electron

```shell
yarn global add electron@22.2.0
```

### 打包说明

> Windows平台打包时候遇到无法下载依赖，可以按照下面的方式处理：

```shell
\AppData\Local\electron-builder\Cache\winCodeSign-2.6.0\
```

```shell
\AppData\Local\electron-builder\Cache\nsis\nsis-3.0.4.1
\AppData\Local\electron-builder\Cache\nsis\nsis-resources-3.4.1
```
