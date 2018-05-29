# hello
Python

import requests

url = "https://www.baidu.com/"
html = requests.get(url).text
html.encoding = 'utf-8'
printf(html)
