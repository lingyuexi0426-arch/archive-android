# 听取哇声一片档案馆 Android APK 项目

这是一个 Android WebView 壳应用，打开现有线上网站：
`https://black-cake-9954.lingyuexi0426.workers.dev/`

## 重要说明
- 本项目本身不是 APK 文件；APK 需由 Android SDK/Gradle 编译。
- 已附 GitHub Actions 自动构建工作流。把本文件夹中的内容上传到一个 GitHub 仓库，进入仓库的 **Actions → Build Android APK → Run workflow**，构建完成后在该次运行页面底部的 **Artifacts** 下载 `tingqu-washeng-yipian-archive-debug-apk`，解压得到 `app-debug.apk`，再传到 Android 手机安装。
- 首次安装可能需要允许浏览器/文件管理器“安装未知应用”。只安装自己构建的文件。
- 此 APK 会联网打开现有网站，不会把网页或 Supabase 数据库复制进 APK；网页无法访问时，APP 内也可能打不开。中国大陆访问可用性仍取决于 Cloudflare/Supabase 网络连通性。
- 此构建是 debug APK，用于个人测试安装，不是上架商店的正式签名包。
