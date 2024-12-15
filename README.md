# 词库

可以用于ibus的libpinyin的词库，基于[https://github.com/thunlp/THUOCL](https://github.com/thunlp/THUOCL) 的数据然后使用[深蓝词库转换工具](https://github.com/studyzy/imewlconverter)处理得来

使用方法: clone仓库，然后在输入法首选项中->用户数据->用户词典->导入，选择data中的文件就可以。

重启一下输入法：`ibus-daemon -drx`

如果可以打出"决明子"，就说明成功了。
