新建一个domains.txt文件，将需要访问的域名写入domains.txt文件中，然后利用脚本进行探活。
也可以用excel表格进行导入，只需要将其与脚本放在同一目录下即可。
脚本运行后会自动在当前目录生成png文件夹，文件夹中存放着脚本爬取的截图。
在第一次访问超时后，会自动进行代理访问，默认是127.0.0.1:7890端口，如需更改可进入py文件中进行更改。
