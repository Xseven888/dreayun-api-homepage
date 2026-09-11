# 即云API宣传首页

这是即云API（DreaYunAPI）的宣传首页，适合通过 GitHub Pages 发布。

- 线上 API 控制台：[api.dreayun.com](https://api.dreayun.com/)
- 页面关键词：即云API、即云AI、即云、DreaYunAPI、大模型 API、API 中转站
- 注册入口：https://api.dreayun.com/register?aff=05yj

## GitHub Pages

在仓库的 **Settings → Pages** 中选择 **Deploy from a branch**，分支选择 `main`，目录选择 `/ (root)`。

## 自定义域名

推荐使用没有承担 API 服务的子域名，例如 `promo.dreayun.com`。在域名 DNS 管理处添加：

- 类型：`CNAME`
- 主机记录：`promo`
- 记录值：`你的 GitHub 用户名.github.io`

然后在 GitHub 仓库的 **Settings → Pages → Custom domain** 填写 `promo.dreayun.com`，保存后开启 **Enforce HTTPS**。

⚠️ 不要把现有的 `api.dreayun.com` 直接指向 GitHub Pages，否则可能覆盖或中断 API 服务。
