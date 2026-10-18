# Lasso Fill

Photoshop 套索填色插件，支持实时预览、填色、擦除、过渡和填色加描边。

## 下载 1.0.0

[下载安装包](https://github.com/TIMETSS/Lasso-Fill/raw/refs/heads/main/releases/1.0.0/LassoFill-Setup-1.0.0.exe) · [使用说明](releases/1.0.0/使用说明.txt) · [SHA-256 校验](releases/1.0.0/SHA256SUMS.txt)

目标环境：Windows x64、Photoshop 2025。面板依赖 Microsoft Edge WebView2 Runtime。

## 安装

1. 保存文档并关闭 Photoshop 与 Lasso Fill。
2. 运行安装包，选择包含 Photoshop.exe 的安装目录。
3. 启动 Photoshop，从「文件 → 自动 → Lasso Fill」打开面板。

更新前自动备份被替换的文件，保留用户设置。

## 功能

- **填色**：用前景色填充当前图层的圈画区域。
- **擦除**：清除当前像素图层的圈画区域，使其透明。
- **过渡**：对当前图层的圈画区域执行平均，得到均匀的平均色。
- **描边**：填充圈画区域，并沿选区边缘描边。

支持不透明度、与 PS 同步的羽化、通用参数关联、填色与描边混合模式，以及前景色／背景色描边。

默认快捷键：填色 **B**、擦除 **E**、过渡 **Shift**。可在设置中自定义。启用时，在画布按住 **Alt** 临时使用 PS 吸管；**Esc** 取消笔画。停用或关闭面板后恢复启用前的工具。

此安装包默认关闭 Debug 运行日志和逐笔性能计时。
