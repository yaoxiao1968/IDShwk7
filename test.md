隐藏方法：用cat info.txt 1.jpg > hiddeninfo.jpg将info.txt文件中的信息（57117204 yaoxiao）隐藏到1.jpg里，生成hiddeninfo.jpg
提取方法：strings hiddeninfo.jpg 在文件最后就能看到含有隐藏信息（57117204 yaoxiao）的字符串
