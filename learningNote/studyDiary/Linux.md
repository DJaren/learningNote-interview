#### Shell 命令解释器， 可编程

ls　　        显示文件或目录

     -l           列出文件详细信息l(list)

     -a          列出当前目录下所有文件及目录，包括隐藏的a(all)

     -p           创建目录，若无父目录，则创建p(parent)

rm               删除文件

     -r            递归删除，可删除子目录及文件

     -f            强制删除

mkdir         创建目录
cd               切换目录

touch          创建空文件

echo            创建带有内容的文件。

cat              查看文件内容

cp                拷贝

mv               移动或重命名

find              在文件系统中搜索某文件

wc                统计文本中行数、字数、字符数

grep             在文本文件中查找某个字符串
            
            
                
             系统管理命令
             
             stat              显示指定文件的详细信息，比ls更详细
             
             who               显示在线登陆用户
             
             whoami          显示当前操作用户
             
             hostname      显示主机名
             
             uname           显示系统信息
             
             top                动态显示当前耗费资源最多进程信息
             
             ps                  显示瞬间进程状态 ps -aux
             
             du                  查看目录大小 du -h /home带有单位显示目录信息
             
             df                  查看磁盘大小 df -h 带有单位显示磁盘信息
             
             ifconfig          查看网络情况 （ip地址）
             
             ping                测试网络连通
             
             netstat          显示网络状态信息
             
             man                命令不会用了，找男人  如：man ls
             
             clear              清屏
             
             alias               对命令重命名 如：alias showmeit="ps -aux" ，另外解除使用unaliax showmeit
             
             kill                 杀死进程，可以先用ps 或 top命令查看进程的id，然后再用kill命令杀死进   
  
            
            查看shell               
                cat / etc/shells
            切换shell    
                chsh -s  
               
            查找find  ~ 代表路径
                find -name"文件名"
                find / -name "文件名"
                find ~ -name "文件名*"
                find ~ -iname "文件名*"
                
                
![](http://ww1.sinaimg.cn/large/b06adeeegy1g0oejh0iezj219u0l9wj3.jpg)                                
            
            检索文件内容
                grep 'partia|
                grep "内容"  target*
                grep -o '正则表达式' //检索
                grep -v 'grep'      // 过滤本身
                
                
           管道操作符  \  遍历操作；
                 find  ~ \gerp "target"
                
           
                   
                
