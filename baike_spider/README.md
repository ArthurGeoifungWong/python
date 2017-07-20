# python__spider
a test of python.(python 简单爬虫爬取指定百科链接和该网页上的标题、阐述)

# spider_main.py
爬虫主程序入口
# url_manager.py
url管理器，将没有爬取过的网页链接放进定义的new_urls的set（）里面，表示待爬取的网页链接
# html_downloader.py
网页下载器（python2.7版本的urllib2模块）
# html_parser.py
网页解析器（beautifulsoup第三方库，html.parser解析器，re模块正则表达式，提取需要的数据）
# html_outputer.py
输出网页（将获取到的数据输出成一个html文件）

PS:第一个爬取的网页是爬虫主程序的入口，可在spider_main.py的root_url进项修改(必须是合法遵守书写规范的域名...)
分析网页结构，通过浏览器的开发者工具查看DOM结构，可以在html_parser.py文件里面使用正则表达式或者其它筛选方法获取节点，从而得到信息。
