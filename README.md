# 脚本简介
该简易脚本用于删除排序之后出现的疑似非同源位点。

该脚本无法严格意义上的删除非同源位点，脚本仅将空缺数目达到一定比例的位点删掉。

# 安装
1.脚本需运行于windows平台

2.脚本需要python3环境
https://www.python.org/downloads/

3.脚本需要安装numpy模块
http://www.numpy.org/

# 使用说明
准备文件：

1.将排序完成的序列导出为fasta文件(后缀必须为.fasta),导出文件时单个序列需在一行中，不要使用Wrap sequence every 80 chars类似的选项导出

2.将fasta文件复制如脚本所在的文件夹中

运行

使用cmd进入该文件夹后运行一下命令
'''
python get_homology.py -0.5
'''

其中0.5表示，如果一个位点内的空缺达到50%即将此列删掉。该值得取值范围在0~1之间。

# 结果
脚本运行结束后会生成一个相同名称的“.fas”文件
---------------------------------------------------------
# Script summary
This simple script is used to remove suspected non-homologous sites that appear after alignment.

The script cannot delete the strictly speaking non-homologous sites. 

The script only deletes the sites with a certain proportion of vacancies.


# Installation
1.The script needs to run on the Windows platform

2.Python3 environments are required for scripts
https://www.python.org/downloads/

3.python3-numpy module are required for scripts
http://www.numpy.org/

# Manual
Prepare the input files:

1.export the alignment sequence as a fasta file(the file suffix must be .fasta). When exporting a file,a single sequence need to be in one line. Do not export files with option like "Wrap sequence every 80 chars".

2.copy all fasta files to the folder where the script resides.
Run the script:

Use cmd to enter the folder and run the command
'''
python get_homology.py -0.5
'''
0.5 indicates that if the vacancy in a site reaches 50%, the column will be deleted. The value ranges from 0 to 1.

# Result

At the end of script, a ".fas" file with the same name is generated.










作者：何健
联系方式：J.he930724@gmail.com

Author: Jian He
Email: J.he930724@gmail.com
