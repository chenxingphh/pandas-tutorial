# pandas-tutorial
pandas基础教程

![Alt text](https://github.com/chenxingphh/pandas-tutorial/blob/main/pandas/pd_01.png)

    Pandas是一个用于数据处理和数据分析的Python三方库。
    1、Pandas可以从各种文件(txt,csv,excel,json...)中导入数据
    2、对数据进行运算操作(选择,拼接,统计,缺失值处理...)
    3、Pandas最主要的数据结构为Series(一维数据)和DataFrame(二维数据)
    
* [pandas_02_dataframe & series](https://github.com/chenxingphh/pandas-tutorial/blob/main/pandas/pandas_02_dataframe%20%26%20series.ipynb)
  - DataFrame & Series说明
  - DataFrame初始化
     - 通过dict初始化
     - 读取文件数据初始化(excel,csv,txt,json)
  - DataFrame保存
     - 保存为指定文件（excel,csv,txt,json）
 
 * [pandas_03_常用基础方法](https://github.com/chenxingphh/pandas-tutorial/blob/main/pandas/pandas_03_%E5%B8%B8%E7%94%A8%E5%9F%BA%E7%A1%80%E6%96%B9%E6%B3%95.ipynb)
   - 查看数据: df.head(),df.tail()
   - 数据大小: df.shape
   - 字段的基础统信息: df.describe()
   - 字段取值的统计: df.value_counts()
   - 新增列 
   - 字段非空信息: df.info()
   - 缺失值处理
      - 缺失值填充
      - 删除缺失数据
   - 遍历DataFrame
   - 行列处理函数: df.apply 
   - 类别编码（将类别列映射为one-hot）

 * [pandas_04_数据选取&分组&修改](https://github.com/chenxingphh/pandas-tutorial/blob/main/pandas/pandas_04_%E6%95%B0%E6%8D%AE%E9%80%89%E5%8F%96%26%E5%88%86%E7%BB%84%26%E4%BF%AE%E6%94%B9.ipynb)
   - 数据选取
     - 选取行&列数据
     - 布尔索引（按指定条件索引）
     - 位置索引(df.icol)
   - 数据分组(Group)
     - sum,average
     - max,min
     - count
   - 数据修改
     - 修改选取数据(df.loc)

 * [pandas_05_多DataFrame处理](https://github.com/chenxingphh/pandas-tutorial/blob/main/pandas/pandas_05_%E5%A4%9ADataFrame%E5%A4%84%E7%90%86.ipynb)
   - 垂直拼接(pd.concat)
   - 水平拼接(pd.merge)
 
