# 雷诺曼卡牌试玩台

一个可直接打开游玩的单文件网页项目，适合放到 GitHub 仓库或 GitHub Pages。

## 项目内容

- `index.html`：GitHub Pages 默认入口页
- `lenormand-playground.html`：同一份试玩页面的保留文件
- `README.md`：项目说明
- `LICENSE.md`：开源许可说明

## 功能

- 36 张雷诺曼卡牌试玩
- 支持 `1 / 3 / 5 / 9 / 36` 张牌阵
- 洗牌、翻牌、一键翻开
- 综合 / 感情 / 工作主题切换
- 简要自动解读
- 页面内置基础规则和牌义速查

## 本地使用

直接打开 `index.html` 或 `lenormand-playground.html` 即可。

注意：
页面里的牌面图片来自 Wikimedia Commons 在线资源，所以第一次打开时需要联网加载图片。

## 放到 GitHub

1. 新建一个 GitHub 仓库
2. 把这些文件上传到仓库根目录
3. 如果要开 GitHub Pages，保留 `index.html` 在根目录即可
4. 在仓库设置里开启 Pages，部署分支选默认分支根目录

## 开源说明

本项目代码和我补充的中文说明文字可按 `MIT` 方式免费开源使用，详见 [LICENSE.md](./LICENSE.md)。

第三方资源说明：

- 页面牌面图源使用的是 Wikimedia Commons 上的 `Das Spiel der Hofnung (The Game of Hope)` 文件
- 该图源文件页可见：[Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Das_Spiel_der_Hofnung_(The_Game_of_Hope).png)
- 雷诺曼基础介绍参考：[Wikipedia - Lenormand cards](https://en.wikipedia.org/wiki/Lenormand_cards)
- 三张牌入门读法参考：[Learn Lenormand](https://learnlenormand.com/3-card-lenormand-spread/)

## 适合继续扩展的方向

- 接入本地图片，改成完全离线版
- 增加单张牌详细弹窗
- 增加更像桌游的发牌动画
- 加入保存抽牌结果和分享截图
