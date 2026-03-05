# MultiplayerCourseBlasterGame

这是一个基于 Unreal Engine 5.3 开发的多人射击课程项目。

## 环境要求

- Unreal Engine 5.3
- Visual Studio 2022（安装“使用 C++ 的游戏开发”工作负载）

## 项目结构

- `Blaster.uproject`：Unreal 项目入口文件
- `Source/Blaster`：核心 C++ 游戏逻辑模块
- `Plugins/MultiplayerSessions`：多人联机会话插件
- `Content`：地图、蓝图与游戏资源
- `Config`：项目配置文件

## 快速开始

1. 克隆本仓库到本地。
2. 使用 Unreal Engine 5.3 打开 `Blaster.uproject`。
3. 如有提示，先生成项目文件并编译 C++ 模块。
4. 在编辑器中打开 `Content/Maps` 下的地图开始运行。

## 版本控制说明

仓库已配置忽略 Unreal 自动生成文件，例如：

- `Binaries/`
- `DerivedDataCache/`
- `Intermediate/`
- `Saved/`

仓库只跟踪源码、配置、插件代码和必要资源文件。
