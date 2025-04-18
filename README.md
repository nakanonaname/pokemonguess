## 这是个基于 2025年 3月 PS vgc regg 各分段加权使用率得来的猜谜游戏

| 文件名 | 用途 |
|--------|------|
| `index.html` | 游戏主页面 |
| `pokemon_question_bank.json` | 宝可梦题库，包含使用率、tags 和图片链接 |
| `move_cn_en.json` | 招式中英对照表 |
| `ability_cn_en.json` | 特性中英对照表 |
| `item_cn_en.json` | 道具中英对照表 |
| `cn_en_dict.json` | 宝可梦名称中英对照表 |

---

### 📁 本地运行

将上述所有文件放入同一目录，**直接双击 `index.html` 打开即可游玩**。

为避免部分浏览器阻止本地读取 JSON 文件，推荐使用简易服务器运行：

```bash
# Python 3
python -m http.server
