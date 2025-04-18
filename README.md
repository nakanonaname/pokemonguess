## 这是个基于 2025年 3月 PS vgc regg 各分段加权使用率得来的猜谜游戏

- tag包含 属性 种族值 蛋种 来自poke.api。
- 手搓字典翻译。
- 所有特性，加权计算后排名前四的招式，排名前三的道具，排名第一的性格，排名前三的队友，排名前二的太晶属性，以及如果有被严重克制的对手也会加入tag。
- 高分段权重50%，中分段25%，中低分段15%，特别低（1000分）10%，确保低分段整活的宝可梦会被记录。

---
## 多形态宝可梦有问题，目前只整合了厄鬼碰，请使用中文搜索后，选择英文名然后加-查看多形态宝可梦
- 比如你想搜索迦勒尔双弹瓦斯，请先搜索双弹瓦斯，选择Weezing，再在后面输入-，会自动联想Weezing-Galar
- 同理有武道熊师，水熊是其他形态，恶熊是原本形态。
- api有点老，轮子转不动，很多bug要慢慢修；；

### 本地运行

将上述所有文件放入同一目录，**直接双击 `index.html` 打开即可游玩**。

为避免部分浏览器阻止本地读取 JSON 文件，推荐使用简易服务器运行：

```bash
# Python 3
python -m http.server
