# csvwritecolumn

按python自带csv开发包，把list类型数据按列写入到csv文件


## csv-write-column.py脚本功能：

脚本功能：


其主要目的用于对nmon原始文件的分析功能上，对cpu、内存、磁盘、网络等每个采样点进行计算后打印，帮助性能测试工程师分析测试过程中的服务器资源利用情况。


根据实际情况需要，也可以用于其他用途


利用python环境自带的csv开发包，实现数据按列写入到excel文件，但是又不想去下载其他excel开发插件（主要是懒），摸索了半天才找到这个简单的方案来实现按列写入。
	
	
## csv-write-row.py脚本功能：


 脚本功能：
 
 一次性读取csv文件中所有内容，然后清空该文件，关闭文件句柄。
 
 
 对文件内容进行处理，添加一列，然后按行逐次写入到该csv文件中。
 
 
 原本是用于nmon结果分析功能，打印各采样点数据的，个人觉得该方法没有按列写入好。
 
 
