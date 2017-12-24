# 矩阵乘法 http://blog.csdn.net/bbbeoy/article/details/72576863

1. 当为array的时候，默认d*f就是对应元素的乘积，multiply也是对应元素的乘积，dot（d,f）会转化为矩阵的乘积， dot点乘意味着相加，而multiply只是对应元素相乘，不相加

2. 当为mat的时候，默认d*f就是矩阵的乘积，multiply转化为对应元素的乘积，dot（d,f）为矩阵的乘积


np.multiply(d,f) 对应元素

np.dot(d,f) 矩阵相乘

# range  arange https://jingyan.baidu.com/article/e6c8503c1e89d6e54f1a188c.html

range返回list

arange返回array
