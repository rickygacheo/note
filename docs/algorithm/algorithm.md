---
title: algorithm
nav_order: 4
---

# Numpy使用
numpy.random.seed函数：seed种子在同一次运行过程中，设置相同的种子数，生成的随机数会是相同的
np.arange(nb):
    函数返回一个有终点和起点的固定步长的排列，如[1,2,3,4,5]，起点是1，终点是6，步长为1。
    参数个数情况： np.arange()函数分为一个参数，两个参数，三个参数三种情况
    1）一个参数时，参数值为终点，起点取默认值0，步长取默认值1。
    2）两个参数时，第一个参数为起点，第二个参数为终点，步长取默认值1。
    3）三个参数时，第一个参数为起点，第二个参数为终点，第三个参数为步长。其中步长支持小数
