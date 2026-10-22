# 更新日志 (Changelog)

本项目的所有重要变更将记录在此文件中。

格式基于 [Keep a Changelog](https://keepachangelog.com/zh-CN/1.1.0/)，
版本号遵循 [语义化版本 2.0.0](https://semver.org/lang/zh-CN/)。

## [Unreleased]

### 计划中

- 代码签名（消除 SmartScreen/杀软误报）
- 在线更新检查

## [1.0.0] - 2026-10-20

首个公开发布版本。

### 新增

- **区域截图**：全局快捷键 `F1` 唤起，框选任意区域，选区支持微调
- **标注编辑**：矩形、椭圆、箭头、画笔、文字工具；马赛克/模糊效果（强度可调，支持矩形/圆形/画笔三种涂抹形状）；12 色标注色板与三档线宽，偏好按功能分别记忆；撤销/恢复
- **滚动长截图**：自动/手动双模式滚动拼接
- **截图贴图**：截图钉在屏幕最前端，随时对照
- **区域录屏**：可选系统声音/麦克风/混合（设备缺失自动降级）；输出 MP4 或 GIF（自动转码）；录制区域中央弹出结束提示气泡，一键打开保存目录
- **安装程序**：中文安装向导，安装路径可选，VC++ 运行库静默安装，可选开机自启，卸载时可选保留用户配置；内置 README 使用说明
- **多显示器支持**：跨屏截图/录屏按物理像素精确捕捉

### 变更

- 用户配置与日志迁移至 `%LOCALAPPDATA%\ScreenShotRecorder`（兼容安装到 Program Files 的权限要求）

[Unreleased]: https://github.com/USERNAME/ScreenShotRecorder/compare/v1.0.0...HEAD
[1.0.0]: https://github.com/USERNAME/ScreenShotRecorder/releases/tag/v1.0.0
