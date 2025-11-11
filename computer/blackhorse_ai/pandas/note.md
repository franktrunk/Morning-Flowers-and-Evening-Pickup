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
