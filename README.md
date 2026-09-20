# AIMKT AIGC 内容标准化交付流程

用于向客户、合作方及团队展示 AIGC 项目的交付机制、标准流程、内容类型、修改标准和制作周期。

共 **15 页**，每页采用 **1600 × 900** 的设计尺寸，保持横版 **16:9** 并随窗口等比缩放。

## 打开方式

下载项目后，用浏览器打开 `index.html`。封面图片、样式和交互均已内嵌，支持离线展示，无需安装依赖。

## 操作

- 左右方向键或底部箭头：翻页。
- 顶端章节导航：跳转章节。
- `F`：切换全屏。
- `Home` / `End`：前往第一页 / 最后一页。
- 图片展示区：使用箭头、圆点或触控滑动切图；聚焦后也可使用左右方向键。

## 替换素材与周期

在 `index.html` 中搜索 `CONTENT_CONFIG`：

- `standard.images`、`portrait.images`、`custom.images`：三类 3:4 展示图片，每类预留四张。填写 `src` 并按需更新 `title`。
- `screenshots.brief`、`screenshots.combination`、`screenshots.feedback`：三处项目截图。
- `production`、`revision`、`levels`：制作与修改周期。

当前业务图片与截图为示意占位。使用相对图片路径时，需将图片一起保存或部署；继续使用内嵌图片可保留单文件离线能力。

## 发布

这是纯静态页面，可放入静态网站托管空间。若使用 GitHub Pages，可在仓库 `Settings → Pages` 中选择从 `main` 分支的根目录发布。

仓库中的代码推送与 GitHub Pages 发布是两个独立步骤。
