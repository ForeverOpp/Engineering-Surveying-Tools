# Engineering-Surveying-Tools  
土木专用测量小工具  
  
# 使用方法  
## 四等水准测量计算（Leveling Surveying.py） 
首先，运行程序，会要求输入一个值，即到目前为止的视距差∑d，如果是第一次输入当然就是0。然后会依次要求输入：后尺下丝、前尺下丝、后尺黑面中丝、后尺红面中丝，中间用空格分隔，然后回车。第二行要求输入后尺上丝、前尺上丝、前尺黑面中丝、前尺红面中丝。输出已经写得很清楚了这里不再赘述，输出第二行最后一个数是用以校验后尺`黑+K-红`与前尺`黑+K-红`之差是否正确的。效果如下：  

      0.3
      ----------------------------------------------------------------------------------------------------
      1390 1737 1790 6477
      1565 1856 1477 6263
      后下	1390	前下	1737	后黑1790		红6477
      后上	1565	前上	1856	前黑1477		红6263
      后距	17.500000	前距	11.900000	后-前黑313	红214	-1
      视距差d	5.600000	视距差ωd	5.900000	中数	313.500000
      ----------------------------------------------------------------------------------------------------
      ----------------------------------------------------------------------------------------------------
      1760 1380 1477 6263
      1892 1573 1826 6513
      后下	1760	前下	1380	后黑1477		红6263
      后上	1892	前上	1573	前黑1826		红6513
      后距	13.200000	前距	19.300000	后-前黑-349	红-250	1
      视距差d	-6.100000	视距差ωd	-0.200000	中数	-349.500000
      ----------------------------------------------------------------------------------------------------
      ----------------------------------------------------------------------------------------------------
      1350 1920 2005 6692
      1540 2095 1445 6232
      后下	1350	前下	1920	后黑2005		红6692
      后上	1540	前上	2095	前黑1445		红6232
      后距	19.000000	前距	17.500000	后-前黑560	红460	0
      视距差d	1.500000	视距差ωd	1.300000	中数	560.000000
      ----------------------------------------------------------------------------------------------------
      ----------------------------------------------------------------------------------------------------
      1870 1400 1512 6302
      2042 1622 1957 6642
      后下	1870	前下	1400	后黑1512		红6302
      后上	2042	前上	1622	前黑1957		红6642
      后距	17.200000	前距	22.200000	后-前黑-445	红-340	-5
      视距差d	-5.000000	视距差ωd	-3.700000	中数	-442.500000
      ----------------------------------------------------------------------------------------------------
      ----------------------------------------------------------------------------------------------------
      1350 1859 1460 6248
      1570 2007 1933 6620
      后下	1350	前下	1859	后黑1460		红6248
      后上	1570	前上	2007	前黑1933		红6620
      后距	22.000000	前距	14.800000	后-前黑-473	红-372	-1
      视距差d	7.200000	视距差ωd	3.500000	中数	-472.500000
      ----------------------------------------------------------------------------------------------------

## 未完待续...

# 结语
如果有同行，可以协助开发，最好是能整一个客户端。
