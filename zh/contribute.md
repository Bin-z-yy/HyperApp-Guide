# 文档贡献奖励计划

开发者精力有限，很难有时间添加各类相关的文档，但是文档对于新手来说又是不可或缺的，为了完善 HyperApp 相关的文档，开发者决定凡是参与编写文档的贡献者均赠送至少一枚 HyperApp 兑换码作为感谢。具体所需要添加的文档以及要求请看下文。

### 文档格式

1. 统一使用 `Markdown` 文件，请参阅 [Github 官方的 Mastering Markdown](https://guides.github.com/features/mastering-markdown/)
1. 不要更改 README 首页文件，我会在首页添加链接
2. 文档要放在各语言子目录下面，比如中文的要放在 `zh` 目录下面，同时按功能放入子目录中（参见下面各个分类的要求）
3. 图片放在同级目录的 `images` 目录里。名字按照 `文档名字 - 图片名字` 或者 `文档名字 - 图片序号`
4. 截图尽量使用手机截图，如果网站没有适配手机版可以使用PC版截图。引用图片使用相对路径 比如 `![](./images/xxx.png)`

## 任务列表


### 厂商使用

讲述各厂商如何创建服务器并添加到 HyperApp 中，同时文档要面向非技术用户。

主要技术点：

* 如何注册账号，并领取各个厂商的试用金，不可以带推广链接。
* 如何创建服务器，描述各个字段的含义、如何选择，比如一定要让用户选择64位的系统。由于兼容性问题，操作系统统一推荐 Ubuntu 16 或者 CentOS 7，不可推荐低版本的系统。
* 如果有防火墙则引导默认开启 80，443端口。并且加一句提醒安装应用后需要设置防火墙才能访问。
* 添加到 HyperApp 时，如何知道主机 IP、端口、用户名、密码。
* 要有一个小节介绍自动添加功能，只要告诉用户如何打开 Web SSH/VPC 就行了。

文档放在 `语言/vendors` 下面。比如 Linode 放在 `zh/vendors/Linode.md`，图片放在 `zh/vendors/images/Linode-1.png`。

- [ ] Google Cloud Engine 
- [ ] Amazon AWS
- [ ] Vultr 
- [ ] Digital Ocean 
- [ ] Linode


### 应用

