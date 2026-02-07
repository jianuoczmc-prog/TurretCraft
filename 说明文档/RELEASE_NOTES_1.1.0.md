# TurretCraft v1.1.0 — Release Notes (diff vs v1.0.0)

## English

### Added

- New **Turret Upgrade System**: turrets now have levels, upgrade slots, and an **Upgrade** action in the Turret GUI.
- New item: **Turret Firmware** (crafting yields **2**).
- New item: **Turret Manual** (localized in-game guide pages).
- New crafting recipes:
    - **Turret Firmware x2** (shaped):
      - Pattern: `RGR / IQI / RCR`
      - R=Redstone, G=Gold Ingot, I=Iron Ingot, Q=Quartz, C=Copper Ingot
    - **Turret Manual** (shapeless): `Book + Turret Firmware`

### Changed/Improved

- Turret GUI improvements: shows **Level**, **Damage**, **Cooldown**, and **Ammo Save**; adds upgrade hint + detailed tooltips for the 6 upgrade slots (Iron / Firmware / Redstone / Gold / Diamond / Netherite Scrap).
- GUI text tweaks:
    - Ammo display: `Ammo: %s / %s` → `Ammo: %s/%s`
    - Range label simplified (removed extra note text).
- Added **Traditional Chinese (zh_tw)** localization.
- Added new GUI textures/icons (`turret_gui_v3`, `turret_gui_v4`, `tc_icons`).

### Fixes/Compatibility

- Multiplayer compatibility: custom projectile entities (Iron Bullet / Frost Shard / Cannonball) now use Forge **NetworkHooks** spawn packets.

---

## 简体中文

### 新增

- 新增 **炮塔升级系统**：炮塔现在有等级、6 个升级槽，并可在炮塔 GUI 中执行 **升级**。
- 新增物品：**炮塔固件**（合成一次产出 **2 个**）。
- 新增物品：**炮塔说明书**（内置多语言说明页面）。
- 新增合成配方：
    - **炮塔固件 x2**（有序合成）：
      - 形状：`RGR / IQI / RCR`
      - R=红石，G=金锭，I=铁锭，Q=下界石英，C=铜锭
    - **炮塔说明书**（无序合成）：`书 + 炮塔固件`

### 修改/优化

- 炮塔 GUI 增强：新增显示 **等级 / 伤害 / 冷却 / 省弹**；加入升级提示，并为 6 个升级槽提供更详细的提示（铁 / 固件 / 红石 / 金 / 钻石 / 下界合金碎片）。
- GUI 文本微调：
    - 弹药显示：`弹药：%s / %s` → `弹药：%s/%s`
    - 射程说明简化（去掉额外注释文本）。
- 新增 **繁体中文（zh_tw）** 本地化。
- 新增 GUI 贴图/图标（`turret_gui_v3`, `turret_gui_v4`, `tc_icons`）。

### 修复/兼容

- 多人兼容性改进：自定义弹丸实体（铁弹 / 冰霜碎片 / 炮弹）现在使用 Forge 的 **NetworkHooks** 生成封包。

---

## 日本語

### 追加

- 新機能：**タレットのアップグレード機能**（レベル／6つのアップグレード枠／GUI内の Upgrade 操作）。
- 新アイテム：**タレットファームウェア**（クラフトで **2個**）。
- 新アイテム：**タレットマニュアル**（ゲーム内ガイド：多言語ページ）。
- 新レシピ：
    - **タレットファームウェア x2**（整形）：
      - パターン：`RGR / IQI / RCR`
      - R=レッドストーン, G=金インゴット, I=鉄インゴット, Q=クォーツ, C=銅インゴット
    - **タレットマニュアル**（不定形）：`本 + タレットファームウェア`

### 変更/改善

- タレットGUI改善：**レベル / ダメージ / クールダウン / 弾薬節約** を表示。アップグレードのヒントと、6枠（鉄/ファームウェア/レッドストーン/金/ダイヤ/ネザライトの欠片）の詳細ツールチップを追加。
- GUI表記の微調整：
    - 弾薬表示：`弾薬：%s / %s` → `弾薬：%s/%s`
    - 射程表記を簡素化（追加注釈を削除）。
- 繁體中文（zh_tw）ローカライズを追加。
- GUIテクスチャ/アイコン追加（`turret_gui_v3`, `turret_gui_v4`, `tc_icons`）。

### 修正/互換

- マルチプレイ互換：弾丸系エンティティ（Iron Bullet / Frost Shard / Cannonball）のスポーンが Forge **NetworkHooks** 経由になりました。

---

## 繁體中文

### 新增

- 新增 **砲塔升級系統**：砲塔現在有等級、6 個升級槽，並可在砲塔 GUI 中執行 **升級**。
- 新增物品：**砲塔韌體**（合成一次產出 **2 個**）。
- 新增物品：**砲塔說明書**（內建多語系說明頁面）。
- 新增合成配方：
    - **砲塔韌體 x2**（有序合成）：
      - 形狀：`RGR / IQI / RCR`
      - R=紅石，G=金錠，I=鐵錠，Q=石英，C=銅錠
    - **砲塔說明書**（無序合成）：`書 + 砲塔韌體`

### 修改/優化

- 砲塔 GUI 強化：新增顯示 **等級 / 傷害 / 冷卻 / 省彈**；加入升級提示，並為 6 個升級槽提供更詳細提示（鐵 / 韌體 / 紅石 / 金 / 鑽石 / 獄髓碎片）。
- GUI 文字微調：
    - 彈藥顯示：`彈藥：%s / %s` → `彈藥：%s/%s`
    - 射程說明簡化（移除額外註解文字）。
- 新增 **繁體中文（zh_tw）** 本地化。
- 新增 GUI 貼圖/圖示（`turret_gui_v3`, `turret_gui_v4`, `tc_icons`）。

### 修復/相容

- 多人相容性改進：自訂彈丸實體（鐵彈 / 冰霜碎片 / 砲彈）現在使用 Forge 的 **NetworkHooks** 生成封包。

---
