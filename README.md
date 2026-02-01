# MultiLogin for Paper 1.21.1

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
![Java](https://img.shields.io/badge/Java-21-orange)
![Gradle](https://img.shields.io/badge/Gradle-8.5-green)
![Minecraft](https://img.shields.io/badge/Minecraft-1.21.1-green)

**基于 MultiLogin (weekly) 官方源码的 Paper 1.21.1 适配版本**

## 📖 简介

此项目是 [MultiLogin](https://github.com/CaaMoe/MultiLogin) 插件针对 **Paper 1.21.1** 服务端的适配版本。通过更新依赖、修复兼容性问题，使插件能在现代 Minecraft 服务器上正常运行。

## 🚀 快速开始

### 下载预构建版本
前往 [Releases](https://github.com/YutaoXT/MultiLogin-for-Paper-1.21.1/releases) 下载最新版本。

### 手动构建
```bash
# 克隆项目
git clone https://github.com/YutaoXT/MultiLogin-for-Paper-1.21.1.git

# 构建插件
./gradlew shadowJar

# 构建结果
# bukkit/build/libs/MultiLogin-Bukkit-Build_unknown.jar