# U3DCF

CF 离线试玩版，Windows 64 位解压即玩。运行所需的 UnityPlayer 和 Mono 已包含，无需安装 Unity 编辑器、Unity Hub 或开发环境。

## 下载与运行

打开 [最新版本 Releases](https://github.com/OldShuxi66/U3DCF/releases/latest)，下载附件 `CF-Offline-v13-Windows-x64.zip`，完整解压后双击 `FreeForAllPlaytest.exe`，再选择地图开始游戏。

请下载 Release 中的游戏 ZIP 附件。GitHub 自动生成的 Source code 压缩包不包含完整可玩游戏。

不要在压缩包内直接启动；请保留 EXE 旁边的数据目录、MonoBleedingEdge、Config 和 DLL 文件。

## 当前版本 v13

- 新寂静岭：个人竞技，1 名玩家 + 27 名人机。
- 刀锋寨、竞技场：个人竞技，1 名玩家 + 13 名人机。
- 运输船：团队竞技，16 对 16，玩家加入蓝队。
- 支持多种枪械、近战武器、高爆手雷、补给箱及连杀奖励。
- 包含手雷反弹/爆炸、Q 切回上一把武器、每 15 杀切换枪族等更新。
- 本地单机，不需要登录或联网；仅提供 Windows x64 运行包。

## 操作

| 操作 | 按键 |
| --- | --- |
| 移动 / 瞄准 | WASD / 鼠标 |
| 射击、刀轻击、投掷手雷 | 鼠标左键 |
| 瞄准、刀重击 | 鼠标右键 |
| 主武器 / 副武器 / 刀 / 手雷 | 1 / 2 / 3 / 4 |
| 切换下一把刀 | 持刀时再按 3 |
| 上一把武器 | Q |
| 换弹 / 跳跃 | R / Space |
| 蹲下 | C 切换，或按住 Ctrl |
| 比分 | 按住 Tab |
| 释放鼠标 | Esc，点击左键重新锁定 |
| 退出游戏 | Alt+F4 |

更多操作说明与配置方法见游戏包内 `README_开始游戏.md`。修改 `Config` 下的人机名字、武器平衡、比赛规则和地图配置后，重启游戏即可生效。

## 验证与反馈

v13 已从 ZIP 解压副本验证文件 SHA-256，以及菜单和四张地图的 Direct3D 11 启动，确认 UnityPlayer、Mono 和配置均从包内加载。验证为本机启动检查，尚未进行无 Unity 新电脑实测或完整对局回归；原有 VFXCopyBuffer 特效警告仍存在。

反馈问题时请提供版本、地图、复现步骤，以及玩家日志 `%USERPROFILE%\AppData\LocalLow\Local Prototype\Free For All Playtest v13\Player.log`。
