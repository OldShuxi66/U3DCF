# U3DCF

CF 离线试玩版，Windows 64 位解压即玩。运行所需的 UnityPlayer 和 Mono 已包含，无需安装 Unity 编辑器、Unity Hub 或开发环境。

## 下载与运行

打开 [v17 设置菜单修复版](https://github.com/OldShuxi66/U3DCF/releases/tag/v17)，下载附件 `CF-Offline-v17-Windows-x64.zip`。完整解压后，打开同名文件夹并双击 `FreeForAllPlaytest.exe`，再选择地图和角色开始游戏。

请下载 Release 中的游戏 ZIP 附件。GitHub 自动生成的 Source code 压缩包不包含完整可玩游戏。不要在压缩包内直接启动；请保留 EXE 旁边的数据目录、`MonoBleedingEdge`、`Config` 和 DLL 文件。

## 当前版本 v17

- 新寂静岭：个人竞技，1 名玩家 + 27 名人机；刀锋寨、竞技场：个人竞技，1 名玩家 + 13 名人机。
- 运输船：团队竞技，16 对 16，玩家加入蓝队。
- 准备界面可选飞虎队、奥摩、灵狐者和树喜。树喜按 F 喷气，按住 WASD 可选择八个方向；击杀刷新技能。
- 喷气前段较快、末段明显减速；从高处冲出后按较低重力缓慢下落。角色技能数值统一在 `Config/CharacterAbilities.json`。
- Esc 打开对局菜单后可用鼠标调整设置；菜单打开时角色不响应移动、视角和攻击，按 Esc 或点击“继续游戏”返回。
- 支持角色语音、枪械与近战武器、高爆手雷、补给箱、伤害数字、狙击两档开镜、枪械近战、动态准星、FAL 榴弹和连杀奖励。
- 本地单机，不需要登录或联网；仅提供 Windows x64 运行包。

## 操作

| 操作 | 按键 |
| --- | --- |
| 移动 / 瞄准 | WASD / 鼠标 |
| 射击、刀轻击、投掷手雷 | 鼠标左键 |
| 当前武器特殊动作 / 刀重击 | 鼠标右键 |
| 主武器 / 副武器 / 刀 / 手雷 | 1 / 2 / 3 / 4 |
| 切换下一把刀 | 持刀时再按 3 |
| 上一把武器 | Q |
| 换弹 / 跳跃 | R / Space |
| 蹲下 | C 切换，或按住 Ctrl |
| 树喜喷气 | F，按住 WASD 选择方向 |
| 开关伤害数字 | T |
| 比分 | 按住 Tab |
| 对局菜单 | Esc 打开/关闭，或点击“继续游戏”返回 |
| 退出游戏 | Alt+F4 |

更多操作说明与配置方法见游戏包内 `README_开始游戏.md`。修改 `Config` 下的文本或 JSON 后，重启游戏即可生效。

## 验证与反馈

v17 已从 ZIP 解压副本校验文件，并完成菜单和四张地图的 Direct3D 11 启动检查；UnityPlayer、Mono 和配置均从发布包加载。这是本机自动检查，仍需在图形游戏中体验声音与手感。

反馈问题时请提供版本、地图、复现步骤，以及玩家日志 `%USERPROFILE%\AppData\LocalLow\Local Prototype\Free For All Playtest v17\Player.log`。

