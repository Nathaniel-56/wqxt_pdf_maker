# 文泉学堂目录添加器

> 感谢[kajweb](https://github.com/kajweb/)同学的[wqxuetang_downloader](https://github.com/kajweb/wqxuetang_downloader)中提供的代码，本项目只是将其中的生成目录部分拿出来单独做成一个小工具，供大家救急使用

## 用法

首先修改`cookies.txt`, 把其中的{InputYoursHere}替换成你的PHPSESSID

python main_pdf.py -i <你的pdf路径> -b <图书的bid>

可以直接输入-i后将你的pdf拖拽到终端里，再输入-b和你的bid

之后会在项目目录下新建一个`OutputPdf`文件夹，里面包含生成的含有目录的pdf

### 欢迎加入文泉学堂讨论群：1047666580
