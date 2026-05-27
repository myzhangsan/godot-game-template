# Godot 游戏模板（Godot Game Template）

基于 Godot 4.6 的现代游戏开发基础框架  
兼容 Godot 4.3+

---

# 项目简介

这是一个适用于 Godot 的完整游戏开发模板。

它已经内置：

- 主菜单
- 设置菜单
- 暂停菜单
- 场景切换
- 加载界面
- 存档系统
- UI 音效
- 背景音乐
- 输入重绑定
- 手柄支持
- 全局状态管理
- 示例游戏场景

适合：

- 独立游戏开发
- Game Jam
- 2D / 3D 游戏
- 商业项目原型
- Steam 游戏

---

# 引擎版本

推荐使用：

- Godot 4.6

兼容：

- Godot 4.3+

---

# 项目目标

在 15 分钟内快速搭建：

- 游戏主菜单
- 设置系统
- UI 框架
- 存档流程
- 游戏状态管理

让开发者能够：

> 专注游戏玩法，而不是重复搭建基础系统。

---

# 功能特性

## 基础功能（Base）

`base/` 目录包含核心功能模块。

### 已实现

- 主菜单
- 设置菜单
- 暂停菜单
- 制作人员名单
- 加载界面
- 开场动画
- 全局设置保存
- 简易配置接口
- 可扩展 Overlay 菜单
- 键盘 / 鼠标支持
- 手柄支持
- UI 音效控制器
- 背景音乐控制器
- Markdown 制作名单解析
- 全局状态管理
- 自动加载配置（Autoload）

---

## 扩展功能（Extras）

`extras/` 目录包含额外功能。

### 已实现

- 关卡加载器
- 关卡进度管理
- 胜利 / 失败系统
- itch.io 自动发布脚本
- Butler 上传支持

---

## 示例项目（Examples）

`examples/` 目录包含示例游戏内容。

### 示例内容

- 示例游戏场景
- 关卡类
- 3 个示例关卡
- 教程窗口
- 胜利 / 失败窗口
- 动画主菜单
- Godot Logo 开场
- 游戏状态管理

---

# 项目结构

推荐结构：

```text
project/
├── addons/
├── game/
│   ├── player/
│   ├── enemies/
│   ├── levels/
│   ├── systems/
│   ├── ui/
│   └── autoload/
├── assets/
├── audio/
├── shaders/
└── docs/
```

---

# 安装方式

# 方法一：Asset Library（推荐）

## 创建新项目

1. 打开 Godot
2. 进入：

```text
Asset Library Projects
```

3. 搜索：

```text
Maaack's Game Template
```

4. 下载模板
5. 创建项目
6. 安装并打开

---

## 添加到已有项目

1. 打开：

```text
AssetLib
```

2. 搜索：

```text
Maaack's Game Template Plugin
```

3. 下载插件
4. 安装到：

```text
addons/
```

5. 重启项目
6. 在：

```text
Project Settings > Plugins
```

启用插件

---

# 方法二：GitHub

## 下载

```bash
git clone https://github.com/Maaack/Godot-Game-Template.git
```

或者下载 Release。

---

## 安装

将：

```text
addons/maaacks_game_template
```

复制到你的项目：

```text
addons/
```

目录中。

---

# 使用方法

运行：

```text
Project > Tools > Run Maaack's Game Template Setup...
```

启动 Setup Wizard。

---

# Setup Wizard 功能

初始化：

- 示例场景
- UI 系统
- 菜单结构
- 游戏状态
- 设置系统

这些文件会从：

```text
/addons/
```

复制到你的项目目录。

你可以自由修改。

---

# 文档

## 基础文档

- Main Menu Setup
- Options Menu Setup
- Game Scene Setup
- Game Saving
- Loading Scenes
- Joypad Inputs

## 高级文档

- Build And Publish
- Automatic Updating
- CICD 发布
- itch.io 上传
- 游戏展示

---

# 支持的项目类型

适合开发：

- RPG
- 横版动作
- 肉鸽
- 平台跳跃
- 俯视角射击
- 解谜游戏
- 视觉小说
- 3D 冒险

---

# 推荐开发流程

## 第一阶段

白盒原型：

- 方块
- 碰撞
- 基础玩法

## 第二阶段

临时素材：

- Kenney Assets
- OpenGameArt

## 第三阶段

正式内容：

- 美术
- UI
- 动画
- 音效

---

# 推荐工具

## 编辑器

- VSCode
- Godot 内置脚本编辑器

## 版本控制

- Git
- GitHub Desktop

## 素材网站

- Kenney
- itch.io
- OpenGameArt

---

# 开发建议

推荐：

- 小步迭代
- 先做玩法
- 不要过度架构
- 不要一开始做 ECS
- 不要过早优化

---

# 社区

Discord：

https://discord.gg/AyZrJh5AMp

---

# 原项目

原作者：

Maaack

GitHub：

https://github.com/Maaack/Godot-Game-Template

---

# License

请查看：

```text
LICENSE.txt
```

---

# 致谢

感谢：

- Godot Engine
- Maaack
- Godot 社区
- 所有独立游戏开发者

---

# TODO

- [ ] 中文本地化
- [ ] 玩家控制器
- [ ] 对话系统
- [ ] 背包系统
- [ ] 战斗系统
- [ ] 存档优化
- [ ] Steam 发布

---

# 当前项目状态

开发中 🚧
