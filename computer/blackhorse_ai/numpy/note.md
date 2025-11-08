# Numpy
## 简介
* 本身由C语言开发，相对来说比较高效
* 高性能科学计算和数据分析的基础包
* ndarray，多维数组（核心）
* 是pandas的基础
* 无需遍历就可以进行快速的矩阵运算

## 创建ndarray
* 通过数组的形式创建
* zeros()/ones()/empty()创建
* 使用arange()函数
* matrix生成二维数组
* rand(), randint(), uinform()
* astype转换类型来创建
* 等比logspace,等差linspace

## numpy的内置函数
### 基本函数
* ceil:向上取整
* floor：向下取整
* rint ：四舍五入
* isnan 判断元素是否为NaN
* multiply：元素相乘
* divide: 元素相除
* abs: 元素的绝对值
* where(condition,x,y)三元运算符

### 统计函数
* np.mean(),np.sum():所有元素的和
* np.max(),np.min():最大值最小值
* np.std(),np.var()：所有元素的标准差、方差
* np.argmax(),np.argmin(),最大值、最小值的下标索引
* np.cumsum(),np.cumprod()，返回一个一维数组，每个元素是前缀元素的累加和、累乘积
* 可以使用axis进行调整按列或者按行

### 比较函数
* any 任一满足条件为true否则为false
* all 任一满足为false否则为true

### 排序函数
* np.sort(arr) 排序后返回新的副本
* arr.sort() 对原数组进行排序

### 去重函数
* unique

## numpy运算
### 基本运算
* 简单的四则运算，对应元素的计算
### 矩阵运算
* 简单的对应元素运算
* 矩阵乘法