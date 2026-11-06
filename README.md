# The Sims 4 Save Viewer / Sims 4 存档查看器

**Website / 网页地址: https://xiyuez1.github.io/TheSims4-family-tree/**

[English](#english) | [中文](#中文)

---

## English

A web tool that reads your The Sims 4 save file. It shows the family tree, towns, lots and households in the browser, and exports the family tree as a GEDCOM (`.ged`) file. You can import the file into genealogy software such as Ahnenblatt, Gramps or MyHeritage.

Everything runs locally in your browser. Your save file is never uploaded.

### Features

- **Family tree viewer.** Pick any Sim to see their ancestors, siblings, partners and descendants. Click a Sim to move the view to them.
- **Towns and lots.** Browse every lot by town, with its residents, bedrooms and bathrooms, number of objects and total object price. Filter for occupied lots, vacant houses, empty land, apartment units and lots with very little furniture.
- **Households.** See every household with its members, home address and funds. Click a member to open their family tree.
- **GEDCOM export** with parents, marriages and death status.
- **Export scope.** Export every Sim with a family or marriage link, every Sim in the save, or only the family of one chosen Sim.
- **Removed ancestors.** The game deletes some long dead Sims. It keeps their gender and family links but not their names, so they appear as "未知" (unknown).
- **Former spouses.** Divorced or widowed spouses are included and marked in the notes.
- Life stage, household and Sim ID are written to each person's notes.
- Pets can be included or left out.

### How to use

1. Open the website.
2. Choose or drag in a save file. Save files are in `Documents\Electronic Arts\The Sims 4\saves\` and are named like `Slot_00000001.save`.
3. Browse the family tree, choose the export scope, then click **下载 .ged 文件** (Download .ged file).

### Importing into Ahnenblatt

1. Open Ahnenblatt and choose **Datei → Öffnen** (File → Open).
2. Set the file type to GEDCOM (`*.ged`) and select the downloaded file.
3. If Chinese or other non English names look garbled, set the character set to UTF-8 when importing.

### Notes

- The game does not record birth or death dates, so the file has no dates. Dead Sims are only marked as deceased.
- The total object price does not include walls, floors or land, so it is lower than the lot value shown in the game.
- The tool has not been tested with every game version. If something looks wrong, please open an issue.
- This is a fan made tool. It is not affiliated with or endorsed by Electronic Arts or Maxis.

### Acknowledgements

The save file structure is based on the protobuf schema in [ts4-save-data-reader](https://www.npmjs.com/package/ts4-save-data-reader) by GameTimeDev.

---

## 中文

一个网页工具。读取模拟市民 4（The Sims 4）的存档，在浏览器里查看族谱、城镇、用地和家庭，并把族谱导出为 GEDCOM（`.ged`）文件。导出的文件可以导入 Ahnenblatt、Gramps、MyHeritage 等族谱软件。

所有处理都在你的浏览器本地完成，存档不会上传到任何地方。

### 功能

- **族谱查看。** 选中任意一个小人，查看他的祖先、兄弟姐妹、配偶和子孙。点击其他小人可以切换中心。
- **城镇与用地。** 按城镇浏览所有用地，查看住户、几房几卫、物品数量和物品总价。可以筛选有人住的用地、空房、空地、公寓单元和家具很少的房子。
- **家庭。** 查看所有家庭的成员、住址和存款。点击成员可以打开他的族谱。
- **导出 GEDCOM**，包括父母、婚姻关系和去世状态。
- **导出范围。** 可以导出所有有亲属或婚姻关系的小人、存档里的全部小人，或者只导出某个小人所在的家族。
- **已被清除的祖先。** 游戏会删掉一些去世很久的小人，只保留他们的性别和亲属关系，不保留名字，所以显示为“未知”。
- **前配偶。** 离婚或丧偶的前配偶也会导出，并在备注里注明。
- 年龄段、所属家庭和 Sim ID 会写在每个人的备注里。
- 可以选择是否包括宠物。

### 使用方法

1. 打开网页。
2. 选择或拖入存档文件。存档在 `文档\Electronic Arts\The Sims 4\saves\` 文件夹里，文件名形如 `Slot_00000001.save`。
3. 浏览族谱，选择导出范围，然后点 **下载 .ged 文件**。

### 导入 Ahnenblatt

1. 打开 Ahnenblatt，选择 **Datei → Öffnen**（文件 → 打开）。
2. 文件类型选 GEDCOM（`*.ged`），选中下载的文件。
3. 如果中文名字显示成乱码，导入时把字符集选为 UTF-8。

### 说明

- 游戏不记录出生和死亡日期，所以文件里没有日期。去世的小人只标记为“已去世”。
- 物品总价不包括墙、地板和地皮，所以比游戏里显示的用地价值低。
- 本工具没有在所有游戏版本上测试过。如果发现问题，欢迎提交 issue。
- 本工具是玩家自制，与 Electronic Arts 和 Maxis 无关。

### 致谢

存档结构参考了 GameTimeDev 的 [ts4-save-data-reader](https://www.npmjs.com/package/ts4-save-data-reader) 中的 protobuf 定义。
