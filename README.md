1)命令行窗口切换到TextProcessor.java文件所在目录  

2)执行 javac TextProcessor.java  

3)执行 java TextProcessor  

4)然后输入两个参数，需要处理的文本和排版宽度，示例如下：  
正常情况：  
The main theme of education in engineering school is learning to teach yourself  
30  
输出预处理后的文本.  
异常情况：  
1.包含异常字符：  
So &nbsp;&nbsp;&nbsp; many whitespaces*  
10  
输出ERROR: Invalid character detected!  
2.宽度超过范围：  
So &nbsp;&nbsp;&nbsp; many whitespaces  
90  
输出ERROR: Width out of range!
