# 喜鹊标书 AI

面向招投标场景的 AI 标书制作平台介绍页

## 页面预览

打开 `index.html` 即可查看。页面使用唯一视觉素材：`assets/hero.png`。请将用户提供的产品图保存为该路径，页面会自动展示；如果图片尚未放入，页面会显示内置的 CSS 占位界面，不影响页面布局。

## 文件说明

```text
.
├── index.html       # 页面入口、产品介绍、流程、FAQ
├── styles.css       # 响应式视觉样式
├── script.js        # 移动端导航与 FAQ 交互
└── assets/
    └── hero.png     # 唯一产品图片，请放入用户提供的图片
```

## 内容结构

- 产品定位：先解析招标文件，再辅助完成标书制作
- 核心能力：招标文件解析、技术标与商务标、施工标专项、企业资料复用、审查与模拟评标
- 工作流程：上传资料、解析评估、调整大纲、生成正文、审查导出
- FAQ：完整投标方案、正文修改、内容相似与人工审核边界
- 外部入口：官网、产品功能页和联系我们页面

## 本地预览

无需安装依赖。可以直接双击 `index.html`，或在当前目录启动静态服务：

```bash
python3 -m http.server 8080
```

然后访问 <http://localhost:8080>。

## 发布到 xique 仓库

将以下文件放到 `yyn13/xique` 根目录，并创建 `assets` 目录放入产品图：

- `index.html`
- `styles.css`
- `script.js`
- `README.md`
- `assets/hero.png`

如果希望 GitHub Pages 直接展示页面，在仓库的 Pages 设置中选择部署分支根目录即可。

## 内容边界

页面中的产品能力、官网链接和风险提示来自现有喜鹊标书 AI 产品资料。AI 生成内容属于可编辑初稿，企业资质、人员、业绩、技术参数、工期、承诺及最终合规性必须由使用者核验；查重和模拟评标结果仅作辅助判断。

## 相关入口

- [喜鹊标书 AI 官网](https://www.xiquebiaoshu.com/)
- [产品功能](https://www.xiquebiaoshu.com/product.html)
- [联系我们](https://www.xiquebiaoshu.com/contact-us.html)
