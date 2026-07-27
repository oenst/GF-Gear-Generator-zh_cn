# GF-Gear-Generator 汉化文件

为 **GF-Gear-Generator** 插件提供完整的中文汉化界面，让你在 Fusion 360 中更高效地设计齿轮。

---

## 关于本项目

[GF-Gear-Generator](https://github.com/CenturySturgeon/GF-Gear-Generator) 是一款强大的 Fusion 360 齿轮生成插件，支持直齿轮、斜齿轮、锥齿轮等多种类型。本仓库提供其完整的中文汉化文件，让你告别英文界面，操作更直观。

> **注意**：使用本汉化文件前，**必须**先安装原版插件，版本1.1.1**。

---

## 特性

- 完全汉化界面文字，包括菜单、对话框和提示信息
- 保留原始插件的全部功能和稳定性
- 一键替换，轻松切换中英文
- 兼容原版所有版本（建议使用最新版）

---

## 下载汉化文件

你可以通过以下方式获取汉化文件：

- **克隆本仓库**  
  `git clone https://github.com/oenst/GF-Gear-Generator-zh-cn.git`
- **国内仓库**  
  Gitee：https://gitee.com/oenst/GF-Gear-Generator-zh_cn
- **直接下载 ZIP**  
  点击仓库页面右上角的 `Code` → `Download ZIP` 并解压

汉化文件包含：
- `PackageContents.xml`
- `Contents/GFGearGenerator.py`

---

## 安装步骤

### 1. 安装原版插件
- 从 [Fusion 360 官方市场](https://marketplace.autodesk.com/apps/0f64c486-b04d-4d5f-89c8-11d66f2acd7a) 安装 **GF-Gear-Generator**，或从 [GitHub 原仓库](https://github.com/CenturySturgeon/GF-Gear-Generator) 手动安装。

### 2. 找到插件安装目录
- 打开 Fusion 360，依次点击 `工具` → `脚本与附加模块`（或按 `Shift+S`）。
- 在弹出的窗口中，点击 `我的脚本` 选项卡，找到 `GFGearGenerator`，右键选择 `在文件夹中显示`（或直接复制路径）。
- 或者手动导航到以下典型路径（根据操作系统）：

| 操作系统 | 路径（默认） |
| -------- | ------------ |
| Windows  | `%APPDATA%\Autodesk\Autodesk Fusion 360\API\Scripts\GFGearGenerator` |
| macOS    | `~/Library/Application Support/Autodesk/Autodesk Fusion 360/API/Scripts/GFGearGenerator` |

### 3. 替换汉化文件
- 将下载的汉化文件中的 `PackageContents.xml` 复制到插件根目录，覆盖原文件。
- 将 `Contents/GFGearGenerator.py` 复制到插件目录下的 `Contents` 文件夹中，覆盖原文件。

> **提示**：建议先备份原文件，以便恢复英文版本。

### 4. 重启 Fusion 360
- 关闭并重新启动 Fusion 360，打开插件即可看到中文界面。

---

## 卸载与还原

如需恢复英文版，请：
1. 再次从原仓库或市场下载原版插件。
2. 用原版文件覆盖汉化文件，或直接重新安装原版插件。

---

## 注意事项

- 本汉化文件仅适用于 **GF-Gear-Generator** 原版，不兼容其他修改版本。
- 如遇汉化后插件无法运行，请检查 Fusion 360 版本是否过旧，建议更新至最新版。
- 若原版更新，汉化文件可能失效，请关注本仓库的更新。

---

## 致谢

- 原插件作者：[CenturySturgeon](https://github.com/CenturySturgeon) 提供了优秀的齿轮生成工具。
- 感谢所有参与翻译和测试的贡献者。

---

## 许可证

本汉化文件采用 [MIT 许可证](LICENSE)，你可以自由使用、修改和分发，但需保留版权声明。

---

## 反馈与建议

如有汉化错误或改进建议，欢迎 [提交 Issue](https://github.com/你的GitHub用户名/GF-Gear-Generator-zh-CN/issues) 或 Pull Request。

---

**Enjoy your gear design in Chinese! 🎉**
