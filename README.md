# 饮食喜爱清单 · Food Preferences

一份持续维护的个人饮食偏好清单。飞书风格 / 高大上排版 / 零依赖单文件。

## 在线访问

部署后将自动生成 GitHub Pages 链接。

## 维护方式

直接编辑 `index.html`：

- **新增食材**：复制现有的 `<span class="chip">食材</span>` 标签
  - 加 `star` 类（`<span class="chip star">`）= 首选偏好
  - 加 `no` 类（`<span class="chip no">`）= 不接受
- **新增排名行**：复制 `.rank .row` 一整段，改名字 + 修改 `data-width="数字"`（0–100）
- **新增注意事项**：复制 `.note` 块，加 `red` 类 = 红色禁忌警告

## 更新流程

```bash
git add index.html
git commit -m "update: 加了车厘子的注释"
git push
```

约 30 秒后，GitHub Pages 自动重新发布。
