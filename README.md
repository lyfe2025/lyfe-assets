# Lyfe Assets (官方资源库)

> Lyfe Wu 个人品牌与内容的官方数字资产、图片及资源库。
> 本仓库配合 [Doocs 微信 Markdown 编辑器](https://md.doocs.org/) 实现自动化图床工作流。

## 🚀 关于本仓库

这是 [Lyfe Wu](https://github.com/lyfe2025) 的静态资源托管中心，主要用于存放和分发：
- 📝 **图床服务**：为公众号、博客、Notion 等平台提供稳定的图片托管。
- 📦 **资源分发**：提供 PDF 报告、模板、配置文件等资源的公开下载。
- 🎨 **品牌资产**：存放 Logo、头像等 VI 素材。

---

## 🛠️ 配置说明 (仅供拥有者参考)

本仓库已配置为 Doocs 编辑器的默认图床。若需重新配置或迁移设备，请参考以下参数：

### Doocs 编辑器配置
- **GitHub 仓库**: `lyfe2025/lyfe-assets`
- **分支**: `main`
- **Token 权限要求**: 必须勾选 `repo` (Full control of private repositories)

### 使用姿势
1. **自动上传**：在 Doocs 编辑器中粘贴截图，图片会自动上传至 `YYYY/MM/DD/` 目录。
2. **拖拽发布**：将本地写好的 Markdown 文件夹拖入 Doocs，自动批量上传图片并替换链接。
3. **CDN 加速**：所有资源默认使用 jsDelivr 全球加速。

---

## 🔗 引用格式 (CDN 加速链接)

所有资源通过 jsDelivr 提供高速访问，国内访问速度快且稳定。引用格式如下：

```bash
https://cdn.jsdelivr.net/gh/lyfe2025/lyfe-assets@main/[文件路径]
```

**示例：**
- **图片引用**：`https://cdn.jsdelivr.net/gh/lyfe2025/lyfe-assets@main/2026/03/17/demo.png`
- **文件下载**：`https://cdn.jsdelivr.net/gh/lyfe2025/lyfe-assets@main/files/report.pdf`

---

## 📂 目录结构规范

建议保持以下目录结构，以便管理：

- `/YYYY/MM/DD/` - **自动化归档图片**（由 Doocs 自动生成，按日期分类）
- `/brand/` - **品牌 VI 资产**（Logo, 头像, 二维码等）
- `/files/` - **公开下载资源**（PDF 报告, Excel 模板, 配置文件）
- `/slides/` - **演示文稿**（演讲 PPT, Keynote）

---

© 2026 Lyfe Wu. All rights reserved.
