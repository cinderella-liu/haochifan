# 好好吃饭

复古像素风格的饮食决策与记录应用。

## 功能

- 决策吃什么（健康 / 快乐双轨推荐）
- 记录实际吃了什么（独立入口，支持补记）
- 历史记录查看
- 饭友圈社交
- 食物库自定义管理

## 部署

### GitHub Pages

1. 进入仓库 Settings → Pages
2. Source 选择 `Deploy from a branch`
3. Branch 选择 `main` / `(root)`
4. 保存后等待部署完成

### 构建 APK

推送代码到 main 分支后，GitHub Actions 会自动构建 APK。

或在 Actions 页面手动触发 `Build Android APK` workflow。

构建完成后，在 workflow 运行详情页的 Artifacts 区域下载 `haochifan-apk`。

## 安装 APK

1. 下载 APK 文件到安卓手机
2. 打开文件管理器，点击 APK 安装
3. 如提示"未知来源"，在设置中允许安装
