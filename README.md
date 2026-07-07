# COCO 个人网站

这是一个参考深色商务风格搭建的 COCO 个人品牌主页，托管在 GitHub Pages 上。

## 网站地址

部署后的访问地址：`https://LIYIFEI1424.github.io/COCO`

## 项目结构

```
COCO/
├── index.html          # 网站首页（深色商务风格）
├── README.md           # 项目说明
├── .gitignore          # Git 忽略文件
└── images/
    └── coco-hero.png   # 首页人物占位图（后续可替换为真实照片）
```

## 页面模块

- **Hero 首屏**：大号姓名、标签、个人标语、经历列表、人物照片
- **关于 About**：个人简介 + 关键数据展示
- **服务 Services**：三个可替换的服务卡片
- **作品 Works**：两个作品/项目占位卡片
- **联系 Contact**：联系方式 + 留言表单

## 如何更新网站

1. 修改 `index.html` 文件中的文字内容
2. 替换 `images/coco-hero.png` 为真实照片
3. 提交代码：`git add . && git commit -m "更新网站"`
4. 推送到 GitHub：`git push`
5. 等待 1-2 分钟，GitHub Pages 自动部署

## 技术栈

- HTML5
- CSS3（内联样式、CSS 变量、响应式布局）
- 原生 JavaScript

## 备注

- 当前图片为 AI 生成的占位图，建议后续替换为 COCO 的真实照片。
- 联系表单目前为前端展示，如需真实提交功能，后续可接入第三方表单服务或后端。
- 后续可使用 CodeBuddy 持续迭代和完善网站内容。
