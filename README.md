# Redstone Spyglass
### 适用于 Mod 的红显材质

第一次画材质, 不是很好看, 还请见谅

后续还会更新其他mod的内容~

这个项目也作 [ShulkerRDK](https://github.com/LiPolymer/ShulkerRDK) 的一个实际应用 Demo

ShulkerRDK 是一个命令行工具, 用于简化MC低代码内容的开发

本项目创建自模板 [ShulkerRDK.RPTemplate](https://github.com/LiPolymer/ShulkerRDK.RPTemplate)

### 贡献指南
如果您想对本项目进行贡献, 请先执行以下步骤:

0. 确保您同意将您的贡献内容在 CC-BY-NC-SA 协议下与本项目一同分发
1. 新增一个 MC 实例, 安装您想要 修改/适配 的 Mod 和 ShulkerRDK *(Neo)Forge 平台请使用Connector加载*
2. 使用您的 MC 实例的游戏目录的绝对路径替换 `shulker/tasks/settings.lvt` 内的 `X:\Path\To\Your\Game`
3. 导出您的 MC 实例的启动脚本为 `client.ps1`, 放置于 `shulker/local/` 文件夹内 (没有的话请新建对应的文件夹)
4. 双击 `srdk.exe` 或在终端内执行 `./srdk` *(Windows下务必使用PowerShell)* 进入交互模式
5. 在交互模式内执行 `dev`, ShulkerRDK 会自动生成本项目并部署到您的 MC 实例, 且会实时监控项目文件夹内的文件变化, 并一定程度上地自动转化/同步 (您可以尝试在这时修改 psd 文件或 aseprite 文件)
6. 最后一件事, 收下我们对您由衷的感谢! 您的每一点贡献都是至关重要的!