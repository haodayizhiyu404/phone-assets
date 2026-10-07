# phone-assets

数字世界引擎（各卡手机插件）的**共享图床仓库**，经 jsDelivr 分发：`https://cdn.jsdelivr.net/gh/haodayizhiyu404/phone-assets@main/img/<文件名>`

## 结构

所有图片平铺在 `img/` 根目录（文件名是 catbox 风格随机名，天然无冲突，子目录只增加 URL 拼接复杂度）。

| 来源 | 文件 |
|---|---|
| 东海往事（通讯录头像/封面、群头像、朋友圈封面、壁纸） | 16 张，catbox 同步 |
| 共享表情包系列（各卡手机插件同一份） | 102 张，自东海往事世界书归档 |

## 维护约定

- **catbox 是唯一事实源**：图片先传 catbox，再把同名文件丢进本仓库 `img/`——引擎侧仓库主、catbox 兜底，两源文件名永远一致。
- 新卡加图：直接往 `img/` 丢文件 + 世界书里写裸文件名即可，不用改目录结构。
- 蒋默卡（linzhou-world 仓库）暂不迁移，维持现状。

## 所属

《东海往事》等角色卡 · 数字世界引擎的配套资产。引擎仓库：[`donghai_wangshi`](https://github.com/haodayizhiyu404/donghai_wangshi)
