# AIShotBall App Store Pages

这个仓库用于托管 AIShotBall 上架 App Store 需要的公开网页。

## 现有页面

- `docs/index.html`：总入口页
- `docs/support.html`：技术支持页，可作为 App Store Connect 的 `Support URL`
- `docs/privacy-policy.html`：隐私政策页，可作为 App Store Connect 的 `Privacy Policy URL`

## GitHub Pages 发布

1. 把这个仓库推送到 GitHub。
2. 打开仓库 `Settings` -> `Pages`。
3. `Source` 选择 `Deploy from a branch`。
4. 分支选择 `main`，目录选择 `/docs`。
5. 保存后等待几分钟生成站点。

发布后 URL 一般类似：

- `https://<username>.github.io/AIShotBall/`
- `https://<username>.github.io/AIShotBall/support.html`
- `https://<username>.github.io/AIShotBall/privacy-policy.html`

## 备注

- `privacy-policy.html` 复制自本地项目 `/Users/carl/Desktop/ShootRecord/docs/privacy-policy.html`。
- `support.html` 当前使用邮箱 `yaozhenxing@yy.com` 作为公开支持联系方式；如果你想换成别的邮箱，改这个文件即可。
