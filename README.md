# five-interview


笔试题-前端：
Implement this design using a front-end framework or HTML/CSS. Submit a Github Link.
https://www.figma.com/design/D0jjN7Twkq0DGm3ZJvQabz/%E5%89%8D%E7%AB%AF%E5%B7%A5%E7%A8%8B%E5%B8%88%EF%BC%88%E5%AE%9E%E4%B9%A0%EF%BC%89?node-id=0-1&p=f
笔试题-爬虫：
 You are required to scrape the job data from this job site and save them to a CSV file.  Write a Python script to scrape job information from the website https://pultegroup.wd1.myworkdayjobs.com/PGI.
 Your script must have pagination functionality to scrape job listings from multiple pages. DO NOT use frameworks like Playwirght, Selenium or DP. Use request instead.

笔试题 - 前端：
使用前端框架或 HTML/CSS 实现此设计。提交一个 Github 链接。
https://www.figma.com/design/D0jjN7Twkq0DGm3ZJvQabz/%E5%89%8D%E7%AB%AF%E5%B7%A5%E7%A8%8B%E5%B8%88%EF%BC%88%E5%AE%9E%E4%B9%A0%EF%BC%89?node-id=0-1&p=f
笔试题 - 爬虫：
要求你从此招聘网站抓取职位数据，并将其保存到 CSV 文件中。编写一个 Python 脚本，从网站https://pultegroup.wd1.myworkdayjobs.com/PGI抓取职位信息。
你的脚本必须具备分页功能，以便从多个页面抓取职位列表。请勿使用 Playwright、Selenium 或 DP 等框架。请使用 requests 库。

my_resume/
├── .vscode/                           # VS Code 编辑器配置
├── node_modules/           # 依赖包
├── public/                             # 静态资源（不经过构建工具处理）
├── src/                                    # 源代码
│   ├── assets/                      		# 图片、样式等资源（会被构建工具处理）
│   ├── components/         		# 组件
│   │   ├── HelloWorld.vue   	# 示例组件
│   │   └── App.vue                  	# 根组件
│   ├── main.js                      		# 入口文件（创建 Vue 实例并挂载根组件）
│   └── style.css                    		# 全局样式文件
├── .gitignore        	           # Git 忽略文件（指定哪些文件不纳入版本管理）
├── index.html                      # 入口 HTML（Vite 会自动注入构建产物）
├── package-lock.json       # 锁定依赖版本（保证环境一致）
├── package.json                 # 项目配置（依赖、脚本命令等）
├── README.md                   # 项目说明文档
└── vite.config.js    		   # Vite 配置文件（可自定义构建、开发服务器等配置）
