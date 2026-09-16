# wedding

一个纯静态的婚礼邀请页面，单文件实现，托管在 GitHub Pages。

## 说明

- 结构与样式全部内联在 `index.html` 里，无构建步骤、无外部依赖
- 页面已设置 `noindex`，不会被搜索引擎收录
- 个人自用的小项目，仅供亲友查看

## 目录结构

```
index.html        页面本体（HTML + CSS + JS 全部内联）
images/           封面、照片墙与微信分享卡片
music/bgm.mp3     背景音乐
```

## 本地预览

双击 `index.html` 即可。或者起一个本地服务（微信分享卡片一类的功能在本地也能正常调试）：

```bash
python -m http.server 8000
```

## 部署

推送到 `main` 分支后，在仓库 Settings → Pages 里选择该分支的根目录即可。

## 备注

练手性质的小项目，结构简单，没有做工程化处理。
