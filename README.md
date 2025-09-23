# douban_top250
1. #结构框架
douban_top250/       # 项目根目录
│
├── src/             # 源代码目录
│   ├── __init__.py
│   ├── main.py      # 主程序入口
│   └── utils.py     # 工具函数（如保存文件函数）
│
├── data/            # 存放数据文件
│   └── movies.csv
│
├── requirements.txt # 项目依赖的库列表
└── README.md        # 项目说明文档

2. #安装依赖库
pip install requests beautifulsoup4 pandas

3. #运行与调试
python src/main.py  #运行main.py文件即可
