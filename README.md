# 启核图策 NexcoreGraph · 官网与安装包

启核图策是面向家庭资源的 AI 智能管家，用拍照入库、可信 AI 与个人资源图谱，把家里的东西变成可查询、可推理、可协作的资源状态。

- 官网：https://yan-stone-computer.github.io/NexcoreGraph-Official/
- 产品演示：https://yan-stone-computer.github.io/NexcoreGraph-Official/demo/
- Releases：https://github.com/yan-stone-computer/NexcoreGraph-Official/releases

## 下载

安装包放在最新 Release：

- `NexcoreGraph-HarmonyOS-unsigned.hap`：HarmonyOS 开发验证包，未签名。
- `NexcoreGraph-Desktop-Setup-1.0.0.exe`：Windows 桌面安装包。

鸿蒙 HAP 需要 DevEco Studio、对应 HarmonyOS SDK 或允许安装开发包的模拟器。正式设备安装应使用团队证书重新签名。

## 仓库结构

- `docs/`：GitHub Pages 官网。
- `docs/demo/`：Web 产品界面。
- `preview/`：官网桌面端与移动端预览。

## 事实边界

模型识别依赖后端配置；应用接续、双设备同步和服务卡片仍需 HarmonyOS 真机复核。网页不把待测项写成已测结论。

