# start-oss-cdn帮助文档
快速部署一个静态完整到阿里云OSS并使用阿里云CDN服务为其进行CDN加速。
<a name="tu2Bs"></a>
## 前期准备
使用该项目，推荐您拥有以下的产品权限 / 策略：

| **服务/业务** | **函数计算** |
| --- | --- |
| 权限/策略 | AliyunOSSFullAccess |
| 权限/策略 | AliyunCDNFullAccess |

<a name="cDPBk"></a>
## 部署&体验

- 🔥 通过 [Serverless 应用中心](https://fcnext.console.aliyun.com/applications/create?template=start-oss-cdn) ， [![](https://cdn.nlark.com/yuque/0/2022/svg/2754189/1659421080072-872339bd-efe6-40c2-980a-2b774a7aea31.svg#clientId=u4260fcfa-1d28-4&crop=0&crop=0&crop=1&crop=1&from=paste&id=u951fe235&margin=%5Bobject%20Object%5D&originHeight=28&originWidth=95&originalType=url&ratio=1&rotation=0&showTitle=false&status=done&style=none&taskId=u90c7646a-d32f-4a27-bacf-aba2236f868&title=)](https://fcnext.console.aliyun.com/applications/create?start-oss-cdn) 该应用。
- 通过 [Serverless Devs Cli](https://www.serverless-devs.com/serverless-devs/install) 进行部署：
    - [安装 Serverless Devs Cli 开发者工具](https://www.serverless-devs.com/serverless-devs/install) ，并进行[授权信息配置](https://www.serverless-devs.com/fc/config) ；
    - 初始化项目：s init start-oss-cdn -d start-oss-cdn
    - 进入项目，并进行项目部署：cd start-oss-cdn && s deploy -y
      <a name="TXTmL"></a>
## 删除
在项目目录下执行`s remove`
> Tips：该操作只会删除cdn域名，并不会删除OSS的bucket。




