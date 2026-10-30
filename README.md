# ALDEVARA — 中世都市経営シミュレーション / Medieval City Simulator / 中世纪都市经营模拟

[日本語](#日本語) · [English](#english) · [中文](#中文)

---

## 日本語

**ALDEVARA** は、ブラウザだけで遊べる中世ヨーロッパ風の都市経営シミュレーションです。
**単一の `index.html` にすべてが入っており、インストールもインターネット接続も不要**です(PC・スマホどちらも可)。

### 特徴
- **14ステージ** — ステージごとに3つのクリア条件と目標日数(★評価)あり
- **盗賊の襲撃と防衛** — 城壁・監視塔・兵営で守備を固めよ。ボスは撃破するまで何度も襲来する
- **区画解放システム** — 🔒で施錠された土地は、市庁舎のレベルアップで順次解放される(Lv1→8マス、Lv2→16、Lv3→26、Lv4→32、Lv5→全34マス)
- **幸福度システム** — 井戸や大聖堂が幸福度を上げ、生産・防衛・人口増加を底上げする
- **3言語対応**(JA / EN / ZH)· **サウンド ON/OFF** · **自動セーブ**(端末内保存)
- 横画面推奨。**縦画面では自動で90°回転して全画面表示**される

### 遊び方
1. `index.html` をダブルクリック(またはスマホにコピーしてブラウザで開く)
2. 左パネルで建物を選び、地図のマスをクリック/タップで建築
3. 建築済みの建物をタップで**アップグレード / 取り壊し**
4. 右パネルで**目標**と**次の襲撃**を確認。上部バーは資源(💰金 🍞食料 🪵材木 🪨石 👤人口 😊幸福 🛡️守備)
5. 一時停止・1x/2x/3x 速度切替、☰メニュー、🔊サウンド、言語ボタンは右上

### 建物早見表

| 建物 | 費用 | 効果 |
|---|---|---|
| 🏰 市庁舎 | 初期建物 | Lvで容量・建築可能設備・守備アップ(Lv2:💰300 🪵100 🪨150〜) |
| 🏠 民居 | 💰50 🪵35 | 人口上限 +7 |
| 🌾 農畑 | 💰45 🪵25 | 食料 +7/日(労働3) |
| 🪓 伐木場 | 💰70 🪨5 | 材木 +4.5/日(労働2) |
| ⛏️ 石切場 | 💰100 🪵15 | 石 +3.5/日(労働3) |
| 🏪 市場 | 💰130 🪵40 | 金 +6/日(労働3・人口10以上) |
| ⚒️ 鉄工房 | 💰160 🪨35 | 守備 +4(労働2・材木消費) |
| 🧱 城壁 | 💰40 🪨50 | 守備 +8 |
| 🗼 監視塔 | 💰70 🪨70 | 守備 +14(労働1) |
| 🛡️ 兵営 | 💰200 🪵70 🪨50 | 守備 +20(労働5・食料-3/日) |
| ⛲ 井戸 | 💰30 🪨80 | 幸福 +4(Lv2まで) |
| ⛪ 大聖堂 | 💰350 🪵120 🪨180 | 幸福 +10(労働2) |

※アップグレードごとに費用は約2.2倍。建物は最大Lv3(井戸のみLv2、市庁舎はLv5まで)

### コツ
- **幸福度は生産・守備・人口成長すべてに影響**。基盤が落ち着いたら井戸・大聖堂を
- **市庁舎のアップグレードは区画解放とセット**。🔓+数字は次に解放されるマス数。序盤は中心8マスしかないため、農畑・民居・防衛の優先順位が重要
- 守備 = 防衛施設 + 人口×0.6(市民兵)。市庁舎Lvと幸福度でさらに上昇
- 襲撃に勝つと**戦利品として金を獲得**。負けると金と食料の30%、人口を失う
- 金は人口×0.15/日の税金が基本収入。市場を足すとさらに増える(人口が必要)
- ボス戦は「弱点!」表示が消えるまで守備を上げてから迎え撃つ

### セーブ・データ
- 進行状況は**ブラウザごとに自動保存**(localStorage)。タイトル画面の「全データ削除」で初期化
- 外部送信は一切なし。完全オフライン動作

---

## English

**ALDEVARA** is a medieval city-management sim that runs entirely in the browser.
**Everything lives in a single `index.html` — no install, no internet needed** (desktop or mobile).

### Features
- **14 stages**, each with 3 win conditions and a par time (★ rating)
- **Bandit raids & defense** — raise walls, towers and barracks. Bosses return until slain
- **District unlocking** — locked plots (🔒) open as the Town Hall levels up (Lv1→8 tiles, Lv2→16, Lv3→26, Lv4→32, Lv5→all 34)
- **Happiness system** — wells and cathedrals boost production, defense and population growth
- **3 languages** (JA / EN / ZH) · **sound toggle** · **autosave** on the device
- Landscape-first; **in portrait the whole game auto-rotates** to fill the screen

### How to play
1. Double-click `index.html` (or copy it to your phone and open it in a browser)
2. Pick a building in the left panel, then click/tap a tile to build
3. Tap any built structure to **upgrade or demolish** it
4. Watch the right panel for **goals** and the **next raid**. Top bar: 💰gold 🍞food 🪵wood 🪨stone 👤people 😊joy 🛡️defense
5. Pause and 1x/2x/3x speed, ☰ menu, 🔊 sound and language live at the top right

### Building cheat sheet

| Building | Cost | Effect |
|---|---|---|
| 🏰 Town Hall | starting building | Level raises capacity, available facilities and defense |
| 🏠 House | 💰50 🪵35 | Pop cap +7 |
| 🌾 Farm | 💰45 🪵25 | +7 food/day (3 workers) |
| 🪓 Lumber Camp | 💰70 🪨5 | +4.5 wood/day (2 workers) |
| ⛏️ Quarry | 💰100 🪵15 | +3.5 stone/day (3 workers) |
| 🏪 Market | 💰130 🪵40 | +6 gold/day (3 workers, pop ≥ 10) |
| ⚒️ Smithy | 💰160 🪨35 | +4 defense (2 workers, uses wood) |
| 🧱 Wall | 💰40 🪨50 | +8 defense |
| 🗼 Tower | 💰70 🪨70 | +14 defense (1 worker) |
| 🛡️ Barracks | 💰200 🪵70 🪨50 | +20 defense (5 workers, −3 food/day) |
| ⛲ Well | 💰30 🪨80 | +4 joy (max Lv2) |
| ⛪ Cathedral | 💰350 🪵120 🪨180 | +10 joy (2 workers) |

*Each upgrade costs ~2.2× more. Most buildings reach Lv3 (Hall up to Lv5).*

### Tips
- **Happiness drives production, defense and population growth** — build wells/cathedrals once the basics run
- **Town Hall levels also unlock new districts** — the 🔓+n badge shows how many tiles the next level opens. With only 8 tiles at the start, build order matters
- Defense = fortifications + pop×0.6 militia, further scaled by Hall level and happiness
- Winning a raid **earns loot gold**; losing costs 30% of gold and food plus population
- Basic income is taxes (pop×0.15/day); markets add more gold but need workers
- In boss stages, keep raising defense until the "weak" warning disappears before the raid hits

### Save data
- Progress **autosaves per browser** (localStorage); wipe it with "Delete all data" on the title screen
- Fully offline — nothing ever leaves your device

---

## 中文

**ALDEVARA** 是一款纯浏览器运行的中世纪欧洲城市经营模拟游戏。
**所有内容都在单个 `index.html` 文件中，无需安装、无需联网**(电脑、手机均可)。

### 特色
- **14个关卡** — 每关3个通关条件与目标天数(★评级)
- **强盗袭击与城防** — 修筑城墙、瞭望塔、兵营。首领在被消灭前会反复来袭
- **区划解锁系统** — 🔒上锁的土地随市政厅升级逐步开放(Lv1→8格、Lv2→16、Lv3→26、Lv4→32、Lv5→全部34格)
- **幸福度系统** — 水井与大圣堂提升幸福度，进而提高生产、防御与人口增长
- **三语言**(JA / EN / ZH)· **音效开关** · **本地自动存档**
- 横屏优先；**竖屏时画面自动旋转90°全屏显示**

### 玩法
1. 双击 `index.html`(或复制到手机用浏览器打开)
2. 在左侧面板选择建筑，点击/触摸地图格子建造
3. 点击已建成的建筑可**升级 / 拆除**
4. 右侧面板查看**目标**与**下次袭击**。顶栏资源:💰金币 🍞食物 🪵木材 🪨石头 👤人口 😊幸福 🛡️防御
5. 右上角为暂停与 1x/2x/3x 速度、☰菜单、🔊音效、语言切换

### 建筑速查表

| 建筑 | 费用 | 效果 |
|---|---|---|
| 🏰 市政厅 | 初始建筑 | 升级提升容量、可用设施与防御(Lv2:💰300 🪵100 🪨150起) |
| 🏠 房屋 | 💰50 🪵35 | 人口上限 +7 |
| 🌾 农场 | 💰45 🪵25 | 食物 +7/天(工人3) |
| 🪓 伐木场 | 💰70 🪨5 | 木材 +4.5/天(工人2) |
| ⛏️ 采石场 | 💰100 🪵15 | 石头 +3.5/天(工人3) |
| 🏪 市场 | 💰130 🪵40 | 金币 +6/天(工人3·需人口≥10) |
| ⚒️ 铁匠铺 | 💰160 🪨35 | 防御 +4(工人2·消耗木材) |
| 🧱 城墙 | 💰40 🪨50 | 防御 +8 |
| 🗼 瞭望塔 | 💰70 🪨70 | 防御 +14(工人1) |
| 🛡️ 兵营 | 💰200 🪵70 🪨50 | 防御 +20(工人5·食物-3/天) |
| ⛲ 水井 | 💰30 🪨80 | 幸福 +4(最高Lv2) |
| ⛪ 大教堂 | 💰350 🪵120 🪨180 | 幸福 +10(工人2) |

*每次升级费用约×2.2。多数建筑最高Lv3(水井Lv2、市政厅Lv5)*

### 技巧
- **幸福度影响生产、防御与人口增长**，基础稳定后请建水井、大教堂
- **市政厅升级同时解锁新区划** — 🔓+数字即下一级解锁的格数。开局仅有中心8格，建造顺序很关键
- 防御 = 防御建筑 + 人口×0.6民兵，并受市政厅等级与幸福度加成
- 击退袭击可获得**战利品金币**;失败将损失30%金币与食物及人口
- 基础收入为税收(人口×0.15/天);市场可增收但需要工人
- 首领关卡请在"弱点!"警告消失、防御达标后再接战

### 存档
- 进度按浏览器**自动保存在本地**(localStorage);标题页"删除全部数据"可重置
- 完全离线运行,不向外部发送任何数据
