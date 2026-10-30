# The Sims 4 Family Tree

**Website / 网页地址: https://xiyuez1.github.io/TheSims4-family-tree/**

[English](#english) | [中文](#中文)

---

## English

A web tool that reads your The Sims 4 save file, shows the family tree in the browser and exports it as a GEDCOM (`.ged`) file. You can import the file into genealogy software such as Ahnenblatt, Gramps or MyHeritage.

Everything runs locally in your browser. Your save file is never uploaded.

### Features

- **Family tree viewer.** Pick any Sim to see their ancestors, siblings, partners and descendants. Click a Sim to move the view to them.
- **GEDCOM export** with parents, marriages and death status.
- **Export scope.** Export every Sim with a family or marriage link, every Sim in the save, or only the family of one chosen Sim.
- **Removed ancestors.** The game deletes some long dead Sims. The tool recovers their names from the save's relationship graph when possible. Otherwise they appear as "未知" (unknown).
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
- The tool has not been tested with every game version. If something looks wrong, please open an issue.
- This is a fan made tool. It is not affiliated with or endorsed by Electronic Arts or Maxis.

### Acknowledgements

The save file structure is based on the protobuf schema in [ts4-save-data-reader](https://www.npmjs.com/package/ts4-save-data-reader) by GameTimeDev.

---

## 中文

一个网页工具。读取模拟市民 4（The Sims 4）的存档，在浏览器里查看族谱，并导出为 GEDCOM（`.ged`）文件。导出的文件可以导入 Ahnenblatt、Gramps、MyHeritage 等族谱软件。

所有处理都在你的浏览器本地完成，存档不会上传到任何地方。

### 功能

- **族谱查看。** 选中任意一个小人，查看他的祖先、兄弟姐妹、配偶和子孙。点击其他小人可以切换中心。
- **导出 GEDCOM**，包括父母、婚姻关系和去世状态。
- **导出范围。** 可以导出所有有亲属或婚姻关系的小人、存档里的全部小人，或者只导出某个小人所在的家族。
- **已被清除的祖先。** 游戏会删掉一些去世很久的小人。如果存档的关系图里还留有他们的名字，工具会把名字找回来，否则显示为“未知”。
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
- 本工具没有在所有游戏版本上测试过。如果发现问题，欢迎提交 issue。
- 本工具是玩家自制，与 Electronic Arts 和 Maxis 无关。

### 致谢

存档结构参考了 GameTimeDev 的 [ts4-save-data-reader](https://www.npmjs.com/package/ts4-save-data-reader) 中的 protobuf 定义。
