# Tensorflow-Tutorial
## 创建张量
### 创建Tensor对象
张量由Tensor类实现，每个张量都是一个Tensor对象

- __tf.constant()函数：创建张量__
 
| tf.constant(value, dtype, shape) | 
| -------------------------------- |


    value:数字/Python列表/Numpy数组 < font face=“微软雅黑”>   
    dtype:元素的数据类型  可省略
    shape:数据的形状  可省略
'''python   
tf.constant([[1,2],[3,4]])   
'''   
