# Statistics Teaching Tools

Lightweight browser-based tools for statistics teachers.

这是一组面向统计课堂的轻量级交互式教学工具。它们都是**单文件 HTML**，不需要安装、不需要后端、不需要账号，下载后直接用浏览器打开即可。

## Why this repo exists

很多统计老师想要的是：
- 能直接投屏上课的工具
- 能快速演示概念的交互页面
- 不依赖复杂部署的课堂资源

这个仓库就是朝这个方向做的：**轻、快、直观、可直接课堂使用**。

## Included tools

## Preview

### Binomial Lab
![Binomial Lab](screenshots/binomial_lab.png)

### Sampling Distribution Bucket
![Sampling Distribution Bucket](screenshots/sampling_distribution_bucket.png)

### 1) `binomial_lab.html`
**二项分布实验室：猫头鹰投递局**

适合讲解：
- Bernoulli trial
- binomial setting
- 成功概率与试验次数如何影响分布
- expected value 与分布形状变化

适用场景：
- AP Statistics
- 高中统计入门
- 课堂演示 binomial distribution

---

### 2) `sampling_distribution_bucket.html`
**霍格沃茨抽样分布演示：魔法木桶抽球**

适合讲解：
- repeated sampling
- sample statistic 的波动
- sampling distribution
- sample size 对抽样分布的影响

适用场景：
- 抽样分布入门
- 比较不同样本量下的稳定性
- 课堂上做“先猜再看”型演示

---

## How to use

### Option 1: Direct download
1. 下载本仓库
2. 打开任意 `.html` 文件
3. 浏览器中直接使用

### Option 2: Git clone
```bash
git clone <your-repo-url>
cd stats-teaching-tools
```
然后双击 HTML 文件，或者拖进浏览器打开。

## Design principles

这个仓库里的工具遵循几个原则：
- **Single-file first**：优先保持为单文件 HTML，方便分享和修改
- **Teacher-friendly**：尽量让老师不需要额外技术配置
- **Classroom-ready**：优先考虑课堂投屏、即时互动和直观展示
- **Concept before polish**：先把统计概念讲清楚，再追求更复杂的功能

## Good fit for

- AP Statistics teachers
- High school statistics teachers
- Introductory statistics instructors
- Teachers building interactive classroom demos

## Current status

目前这是一个**早期但可用**的教学工具集合。

后续可以继续扩展：
- 更多概率模拟工具
- 置信区间 / 假设检验可视化
- 正态分布 / t 分布演示
- 数据分析课堂小工具

## Repo structure

```text
stats-teaching-tools/
├── README.md
├── LICENSE
├── binomial_lab.html
├── sampling_distribution_bucket.html
└── random_name_picker_dark.html
```

## License

This project is released under the **MIT License**.


## GitHub Pages

After enabling GitHub Pages for this repository, the tools can be opened from the project homepage directly.

Suggested Pages entry URL:

- `/` → project landing page
- `/binomial_lab.html` → Binomial Lab
- `/sampling_distribution_bucket.html` → Sampling Distribution Bucket
