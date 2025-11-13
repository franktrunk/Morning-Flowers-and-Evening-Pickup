# Pandas
## 创建series和dataframe
### series
* series是一维容器，series表示DataFrame的每一列，可以吧DataFrame看作由Series对象组成的字典，key是列名，值是Series，每个元素的数据类型必须相同
* 创建的时候可以通过index参数来指定行索引
* 用numpy的ndarray对象创建
* 直接传入python列表，构建series对象
* 传入python列表，构建series对象，并且指定行索引
* 通过元组方式创建series对象
* 通过字典方式创建series对象

### dataframe
* 字典方式构建
* 列表+元组

## series常用操作

### series常用属性
* head属性，默认前5个
* loc和iloc索引和行号
* shape和size维度和元素个数
* values所有的值
* index/keys()所有的索引
* T转置

### series常见的方法
* 看代码吧

### series的布尔索引

### serie 的运算
* series和数值运算，数值会和series的每个值运算
* 两个series之间的计算，如果长度一致，会按照对应的元素进行逐个计算
* 两个series之间计算，如果长度不一致，则对应元素计算，不匹配的元素用nan填充
* series之间进行计算时，数据尽可能会依据索引来计算，优先计算索引一样的数据

## dataframe

### 常用属性

### 常用函数

### 布尔索引

### DataFrame对象的计算
* dataFrame对象和数值运算，把数值作用到每个dataframe上，但是要注意要求对象必须全是数值
* df和df之间的运算，对应元素相加，如果索引不匹配，则用nan填充

### 更改series和dataframe

### 导入和导出数据

## 数据分析入门

### DataFrame加载指定行、列的数据
### DataFrame对象-分组聚合
### DataFrame对象-分组转换
### 基本绘图
### 常用的统计值的方法
### 常用排序方法
###  综合举例

## 数据组合
### concat函数
### merge函数

## 缺失值处理
### 缺失值及判断
* 在pandas中，缺失值用NAN，nan，NaN来表示，它们都是一样的，不是false，也不是0，表示什么都没有
* 用isnull和isna 判断是否为空，与之对应有notnull ,notna,也可以用于判断数值

### 缺失值的处理
* 删除
* 填充

## apply函数

### 对series的用法
### 对DataFrame的用法
* apply函数作用于df对象，默认传入的是axis=0(整列)数据，不是像series一样，逐个元素传递的

### 向量化函数介绍
### 接收lambda表达式写的匿名函数