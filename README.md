# IELTS Vocabulary｜雅思词汇学习中心

一个零构建步骤的静态雅思词汇学习网站，使用 HTML、CSS 和原生 JavaScript 编写。

## 当前功能

- 学习首页：词库数量、掌握数量、收藏数量、每日目标与今日推荐
- 单词词库：按主题筛选、搜索单词或中文释义
- 记忆学习：单词卡片、音标、中文释义、例句和浏览器语音朗读
- 单词测试：四选一英译中练习
- 我的生词本：收藏与取消收藏
- 学习设置：每日目标、美式/英式语音选择、重置本地学习数据
- 使用 localStorage 保存学习记录，无需数据库或账号
- 手机、平板和桌面端自适应布局

## 本地预览

直接用浏览器打开根目录中的 `index.html` 即可。

## 免费发布到 GitHub Pages

1. 打开仓库的 **Settings**。
2. 左侧选择 **Pages**。
3. 在 **Build and deployment** 下，将 **Source** 设为 **Deploy from a branch**。
4. Branch 选择 **main**，文件夹选择 **/(root)**，点击 **Save**。
5. 等待 GitHub Pages 部署完成。仓库名较长，发布地址通常为：

   https://ceciiswcx2511.github.io/https-github.com-ceciiswcx2511-IELTS-Vocabulary/

## 数据说明

学习记录只保存在当前浏览器的 localStorage 中。清除浏览器数据或更换设备后不会自动同步。词库目前是可扩展的示例词汇集合；发音使用浏览器的语音合成功能，实际可用声音取决于设备和浏览器。

## 文件结构

- `index.html`：网站页面、样式、词汇数据和交互逻辑
- `README.md`：项目说明与部署步骤
