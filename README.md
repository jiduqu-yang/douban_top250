### 🎬 豆瓣Top250电影数据分析
**内容**：使用Python爬取豆瓣Top250电影数据，分析高分电影的共性特征，包括导演、类型、评分分布等维度

**项目结构**：
```
douban_top250/
├── src/                 # 源代码
│   ├── main.py         # 主爬虫程序
│   └── utils.py        # 工具函数
├── data/               # 数据文件
│   └── movies.csv      # 电影数据集
└── analysis/           # 数据分析
    ├── basic_analysis.py    # 基础分析
    └── visualization.py     # 可视化
```

### 环境要求
- Python 3.6+
- 安装依赖：`pip install requests beautifulsoup4 pandas seaborn matplotlib`

### 运行示例
```bash
# 运行豆瓣Top250爬虫
python src/main.py

# 进行数据分析
python analysis/basic_analysis.py
```

---

*持续更新中，欢迎Star关注！⭐*
