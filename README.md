### 《Real brands_Item descriptions_QoL enhancement_ and so on》简体中文汉化及兼容性修复



**（适配 Zero Sievert 游戏版本 1.2.24）**

------



### 严正声明



- 本项目**并非**原创 Mod，我**不是**原作者。
- 所有功劳归于原作者 **[BLUEF0XES]**。
- **原 Mod 链接：** https://www.nexusmods.com/zerosievert/mods/133
- 本仓库（或补丁）的上传遵循原 Mod 的许可证。
- **重要：** 根据原作者的授权许可，本项目**不会**开启 GitHub Sponsors 或接受任何形式的捐赠。

------



### 前置需求 (必须安装)



1. **《Zero Sievert》** 游戏本体 (已测试版本 v1.2.24)。
2. **原版 Mod：** [Real brands_Item descriptions_QoL enhancement_ and so on](https://www.nexusmods.com/zerosievert/mods/133)
3. **LazyDataLib：** (原版 Mod 的前置 Mod，请在 N 网上自行搜索并安装最新版)

------



### 安装说明



本项目是一个**修复与汉化补丁**，它**不能**独立运行。您必须先安装原版 Mod。

**推荐使用 Vortex Mod 管理器：**

1. 像平常一样，通过 Vortex 安装原版 Mod (mods/133) 及其所有前置 Mod (如 LazyDataLib)。
2. 从本页面下载 .zip 压缩包 (点击 `Code` -> `Download ZIP`)。
3. 解压 .zip 包，您会得到一个 `gamedata` 文件夹，里面包含了所有已修复和汉化的 `.json` 文件（如 `weapon.json`, `w_mod.json` 等）。
4. **[关键步骤]** 找到您的 Vortex Mod 暂存文件夹 (Mod Staging Folder)。
5. 进入 `.../zerosievert/Real brands_Item descriptions_QoL enhancement_ and so on.../ZS_vanilla/` 目录。
6. 将您解压得到的 `gamedata` 文件夹**复制**到这里，**选择“全部替换”**，以覆盖原 Mod 的旧文件。
7. 返回 Vortex，点击**“部署 Mod” (Deploy Mods)**。
8. 启动游戏。

------



### 本补丁包含以下内容：



1. **完全汉化：**

   - 对 Mod 内所有物品（武器、配件、消耗品、护甲、背包、医疗品、任务物品、手榴弹和技能书）的 `description` 字段进行了完整的简体中文汉化。
   - 汉化严格遵循游戏世界观（例如使用 "EC-74" 而非 "AK-74"，保留 "Zippo" 等品牌名）。

2. **崩溃与兼容性修复 (适配 v1.2.24)：**

   - 修复了原 Mod（一个过时版本）在新版游戏上的多个崩溃问题。

   - **[修复] `Item not recognised` 崩溃：** 通过合并新版游戏数据，解决了因找不到 `mp9_45`、`aug`、`saiga12` 及其弹匣（如 `mod_saiga_12_magazine5`）而导致的崩溃。

   - **[修复] `Item not recognised` 崩溃 (part 2)：** 修复了 `ammo.json` 和 `armor.json` 中缺失的新物品（如 `ammo_12x70_buckshot_ap` 和 `armor_killa_2`）定义。

   - **[修复] 配件兼容性：** 同步了所有旧配件（如消音器、瞄准镜）的 `weapon_id` 兼容性列表，使其能正确安装到 `mp9`、`aug` 等新武器上 。

------



### 免责声明



- 请自行承担使用本 Mod 的风险。
- 安装前请务必备份您的存档和游戏文件。
- 对于因使用本补丁而导致的任何游戏崩溃、存档损坏或数据丢失，我概不负责。
