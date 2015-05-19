# 使用方法
1 下载并解压缩dex-method-counts，打开dos命令窗口
2 用ant或者gradle编译
切换到dex-method-counts目录下  ant  jar
\dex-method-counts\build\jar目录下会生成一个dex-method-counts.jar文件
3 切换到该目录下，执行命令： java -jar dex-method-counts.jar  path\*.apk
path\*.apk就是你统计的某项目的方法。

 java -jar dex-method-counts.jar  C:\Users\lifeix\Desktop\Pintimes.apk 
 java -jar dex-method-counts.jar  C:\Users\lifeix\Desktop\Headline.apk > C:\Users\lifeix\Desktop\info.txt
 
 http://blog.csdn.net/t12x3456/article/details/40837287
 