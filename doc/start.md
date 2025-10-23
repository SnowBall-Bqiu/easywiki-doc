# 安装指南

## 1.选择版本

目前我们有两个版本，一个是有PHP的，一个是纯HTML的。以上两种的功能都是一样的。全部版本请前往[releases查看](https://github.com/SnowBall-Bqiu/easywiki/releases)

|              | HTML | PHP |
| ------------ | ---- | --- |
| 是否有WX QQ自动防红 | 否    | 是   |

---

## 2.下载

您可以访问我们的github仓库，下载我们的代码。或者点击下面的链接下载最新版本。

[Github](https://github.com/SnowBall-Bqiu/easywiki/releases)

---

## 3.部署

目前我们的部署方式有两种，一种是纯HTML部署，一种是PHP部署。具体的您可以根据实际来选择。

### 3.1 纯HTML部署

纯HTML部署是指您直接将下载的HTML文件放到您的服务器上，然后就可以直接访问了。或者是使用GitHub Pages，或者小黄云（cloudflare）又或者是其他一些静态网站托管平台。

### 3.2 PHP部署

这里我们使用宝塔举例，您也可以使用其他面板。

1. 首先您需要安装PHP环境，如果您没有安装PHP环境，您可以使用宝塔的安装PHP环境功能。
   ![alt text](assets/img/image.webp)
   这里您可以选择编译安装或者是急速安装。
2. 安装Web服务器。
   ![NG](assets/img/image-1.webp)
   这里我们使用NGIX。因为我们目前已经安装好了，就不展示了。
3. 创建网站
   ![alt text](assets/img/image-2.webp)
   这里我们创建了一个网站，填写好您的域名，选择好PHP版本就可以了。
4. 配置网站

![alt text](assets/img/image-3.webp)
点击网站根目录，来到根目录。
![alt text](assets/img/image-4.webp)
上传项目文件
访问您设置的域名即可使用！
![alt text](assets/img/image-5.webp)
