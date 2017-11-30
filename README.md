# latex2word
使用 docverter 将latex文档转化为word

因为直接使用Js发送请求到docverter会出现跨域问题，所以使用nginx做代理，开启本地 8088端口代理到docverter api地址。
使用方法

1.修改需要转换latex文档到utf-8编码(记事本另存为就可以)
2.打开nginx 代理（配置文件在项目里）
3.打开页面，选择好要转换的文件，submit，成功！
