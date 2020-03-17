# Script summary
This simple script is used to remove suspected non-homologous sites that appear after alignment.

The script cannot delete the strictly speaking non-homologous sites. 

The script only deletes the sites with a certain proportion of vacancies.

Scripts can work with multiple files in parallel.


# Installation
1.The script needs to run on the Linux platform

2.Python3 environments are required for scripts

3.Module of Numpy, Pandas and Biopython are required for scripts


# Manual
1. Modify the number in line 77 of the script, and delete each locus when the gap ratio in each locus exceeds that ratio.

2. Modify the number at line 124 of the script, which indicates the maximum number of processes used to run the script.

3. Put the alignment file in fasta format to be analyzed in a folder with the script.


# run
'''
python get_homology.py
'''


# Result

When the script finishes running, a ".fas" file with the same name is generated.

----------



# 脚本简介
该简易脚本用于删除排序之后出现的疑似非同源位点。

该脚本无法严格意义上的删除非同源位点，脚本仅将空缺数目达到一定比例的位点删掉。

脚本可以并行处理多个文件。

# 安装
1.脚本需运行于Linux平台

2.脚本需要Python3环境

3.脚本需要安装Numpy、pandas、biopython模块


# 使用说明
1. 修改脚本第77行数字，当每个位点中的gap所占比例超过该比例则将该位点删除。

2. 修改脚本第124行数字，该数字表示最多使用多少个进程运行该脚本。

3. 将需要进行分析的fasta格式的alignment文件与该脚本放入一个文件夹中。



# 运行
'''
python get_homology.py
'''


# 结果
脚本运行结束后会生成一个相同名称的“.fas”文件

-------



Author: Jian He
Email: J.he930724@gmail.com
