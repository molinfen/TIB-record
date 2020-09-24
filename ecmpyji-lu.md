> # 程序修正记录

1. 反应3NTD4pp的gpr的修正，从b0383 or b4213 or b0383→b4213 or b0383，在workflow\_construction脚本中修改，未添加注释

2. 单词拼写修正，solveing→solving，以及python文件中250行的拼写错误

3. 将程序以及文件中kcat修改为kapp，同时饱和度修正为1.0

4. 程序中添加了一些print语句

5. 计算24种底物最大生长速率时，没有关闭\["EX\_dha\_e", "EX\_pyr\_e", "EX\_5dglcn\_e", "EX\_xan\_e", "EX\_fum\_e", "EX\_succ\_e", "EX\_for\_e", "EX\_glcn\_e"\]  
   这些反应，代码方面是添加了注释，需进一步确认更改



