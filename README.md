# python__spider
a test of python.(python 简单爬虫爬取指定百科链接和该网页上的标题、阐述)

spider_main.py
#  爬虫主程序入口
url_manager.py
#  url管理器，将没有爬取过的网页链接放进定义的new_urls的set（）里面，表示待爬取的网页链接
html_downloader.py
#  网页下载器（python2.7版本的urllib2模块）
html_parser.py
#  网页解析器（beautifulsoup第三方库，html.parser解析器，re模块正则表达式，提取需要的数据）
html_outputer.py
#  输出网页（将获取到的数据输出成一个html文件）



