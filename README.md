# 官方版本移步[pengzhile/pandora-cloud-serverless](https://github.com/pengzhile/pandora-cloud-serverless)

# Pandora-Vercel
本项目修改了 [Pandora-Cloud](https://github.com/pengzhile/pandora-cloud) 的Web UI，又在[Pandora-Vercel](https://github.com/chrysoljq/pandora-vercel) 的基础上进行了修改，实现了本地修改后上传至Vercel进行部署。

# Example
[Example-Vercel](https://chat1.zhile.io)


## **环境变量**
#### `CHATGPT_API_PREFIX`  
对话 api 请求地址，默认为 `https://ai.fakeopen.com`，可以设置为你的部署后的域名（仅限 vercel），如测试网址 `https://pandora-vercel-lovat.vercel.app`，或其他反向代理地址（任意平台）。

#### `LOGIN_LOCAL`  
是否启用账号密码登录。Pandora 现已支持直接登录，故默认为 `True`或 1。
