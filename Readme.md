## 格式
- 一级标题 \# 
- 二级标题 \## 
- 代码块 <br>
\`\`\`[lang] <br>
[code] <br>
 \`\`\`

## 示例

# Role
人物属性
## LevelUp <attr slider=true trigger=true>
等级提升
```lua
role:SetLevel(role.level + 1)
```
---
# Dungeon
副本

### 生成yaml
```yaml
- key: Role
  value: 人物属性
  nodes:
    - key: LevelUp
      value: 等级提升
      code:
        lua: ''
        cpp: ''
      attr:
       - slider: true
       - trigger: true
```
