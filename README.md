🌟 项目简介
一个用于收集豆瓣Top250电影数据的Python网络爬虫。

📁 项目结构
text
douban_top250/                    # 项目根目录
│
├── src/                         # 源代码目录
│   ├── __init__.py
│   ├── main.py                  # 主程序入口
│   └── utils.py                 # 工具函数（如保存文件函数）
│
├── data/                        # 数据存储目录
│   └── movies.csv              # 输出数据文件
│
├── requirements.txt             # 项目依赖
└── README.md                   # 项目说明文档
⚙️ 安装步骤
前置要求 / Prerequisites
Python 3.6 或更高版本

pip 包管理器

安装依赖 / Install Dependencies
bash
pip install requests beautifulsoup4 pandas
🚀 运行方法 / Usage
运行主程序：

bash
python src/main.py
爬取的数据将保存到 data/movies.csv 文件中。

📊 功能特点 / Features
爬取电影标题、评分等详细信息

以CSV格式保存数据

易于扩展和修改
