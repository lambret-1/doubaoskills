# 豆包自定义技能备份

本仓库备份了 lambret-1 在豆包工作模式下安装的自定义技能。

## 技能列表

| 技能名 | 用途 |
|--------|------|
| `novel-outline` | 小说改编短剧大纲（五件套） |
| `novel-characters` | 角色设定卡（含出图/TTS提示词） |
| `novel-art` | 场景+道具美术设定 |
| `novel-script` | 剧本（节拍流） |
| `novel-storyboard` | 分镜表（H3提示词） |
| `character-refs` | 角色参考图资产 |

## 安装方法

把对应目录复制到豆包技能目录：

```bash
cp -r novel-outline ~/.doubao/agent_mode/workspace/.user_skills/
cp -r novel-characters ~/.doubao/agent_mode/workspace/.user_skills/
# ... 其他同理
```

## 版本

- 备份日期：2026-10-13
- 已升级：novel-art 和 novel-characters 的 render 脚本支持自动输出「豆包出图提示词」和「即梦AI出图提示词」中文段落
