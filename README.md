# sass-demo
自学sass，基于sass的小demo

# 执行步骤： 
1、去到sass-demo目录，输入cmd； 2、输入命令行: sass --style expanded sass:stylesheet -w // 监控scss文件变化


##使用sass的步骤

##1、创建目录：eg.如下
    -- sass-demo
        --sass
        //--stylesheet
        --index.html
##2、去到对应的目录下打开命令窗口，监听sass下的所有sass文件：
    命令语句：sass --style expanded sass:stylesheet --watch
    语句解析：--style expanded   ======= 生成的css排版格式（编译风格）。值有四种：详见官网；
              sass:stylesheet   ======= sass是存放scss文件的目录；stylesheet是生成的css文件存放的文件夹
              --watch   =============== 表示监听整个sass文件或目录，当修改内容是自动编译
              
     结果：会自动产生stylesheet目录，且在stylesheet目录下自动生成与sass（或scss文件）相对应的css文件
     
