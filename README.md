### 前言：
该服务端原为CatServer，实体更新和玩家更新已经被魔改成异步的了，目前不确定是否有线程安全问题，请不要用到您的生产环境中，您忽视该段所造成的一切后果均与本人无关。
### 构建：
linux运行：unzip patches.zip && unzip src.zip && bash gradlew setup genPatches build
windows:解压patches.zip和src.zip后cmd运行gradlew.bat setup genPatches build
两者运行完后jar可以在build/distributions中找到

[![MultiThreadCS Build Task](https://github.com/NaturalGroup/MultiThreadCatServer/actions/workflows/gradle.yml/badge.svg)](https://github.com/NaturalGroup/MultiThreadCatServer/actions/workflows/gradle.yml)

### 注意：
本插件已迁移，新地址: https://github.com/eelibrary/skylight
