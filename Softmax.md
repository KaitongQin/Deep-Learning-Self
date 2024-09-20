# Softmax Regression
## 1. 从回归到多类分类
### 1.1 回归
- 单连续数值输出
- 自然区间**R**
- 跟真实值的区别作为损失

### 1.2 分类
- 通常是多个输出
- 输出`i`是预测为第`i`类的置信度
- 方法
    - 一位有效编码 $y_i=1$ 
    - 最大值最为预测 $\hat y = argmaxo_i$
    - 更置信的识别正确类 $o_y-o_i\geq \delta(y, i)$

### 1.3 交叉熵
$$
H(p,q)=\sum_i -p_ilog(q_i)
$$
将它作为损失
$$
l(y,\hat y)=-\sum_i y_i log \hat y_i=-log \hat y_y
$$

