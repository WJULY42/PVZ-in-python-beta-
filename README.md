# Plant vs Zombies – Enhanced Edition  
# 植物大战僵尸 – 增强版

## English

A simplified tower defense game based on the classic *Plants vs. Zombies*, implemented with Python's Tkinter library.

### Features
- Plant sunflowers, peashooters, snow peas, potato mines, cherry bombs, and walnuts
- Normal zombies and conehead zombies with slowing effect
- Lawn mowers automatically clear an entire row of zombies
- Independent sun production timer for each sunflower
- Cherry bomb and potato mine have area damage
- Toggle health bars for plants and zombies
- 5 waves of zombies, victory after all waves

### Requirements
- Python 3.6+
- Standard libraries: tkinter, random, time, os

### How to Run
```bash
python PVZ.py
```
Controls

    Click plant buttons at the bottom to select a plant (requires enough sun)

    Click on the lawn grid to plant

    Click "Toggle Health" to show/hide health bars

Custom Assets

Place images in the assets/ folder with the same filenames as in the code. If missing, the game will fallback to simple shapes.
中文

基于经典游戏《植物大战僵尸》的简化塔防游戏，使用 Python 的 Tkinter 库实现。
功能特点

    可种植向日葵、豌豆射手、寒冰射手、土豆雷、樱桃炸弹、坚果

    普通僵尸和路障僵尸，具备减速效果

    小推车可清除整行僵尸

    每株向日葵独立生产阳光

    樱桃炸弹和土豆雷拥有范围伤害

    可切换显示植物和僵尸血量条

    共 5 波僵尸进攻，通关胜利

运行要求

    Python 3.6+

    标准库：tkinter, random, time, os

如何运行
bash

python PVZ.py

操作说明

    点击下方植物按钮选择植物（需足够阳光）

    在草坪网格上点击种植植物

    点击「显示血量」按钮切换血量显示

自定义图片

将图片放入 assets/ 目录，文件名需与代码中一致。缺失图片时游戏会自动使用简单图形代替。
