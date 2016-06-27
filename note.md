<script type="text/javascript"
  src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML">
</script>


#笔记
##数学-线性代数
###行列式
+ **n阶行列式的性质**

    + **性质1** 行列式的行与列（按原顺序）互换，其值不变。

    + **性质2** 行列式对任意一行按下式展开，其值相等
    ![alt text](https://github.com/zhanghaocore/Note_ML/blob/Note_ML_local/mathImg/hanglieshi_nature_2.png "n阶行列式的性质2")
    + **性质3**（线性性质）有以下两条：
    ![alt text](https://github.com/zhanghaocore/Note_ML/blob/Note_ML_local/mathImg/hanglieshi_nature_3.png "n阶行列式的性质3")
    + **推论1** 某行元素全为零的行列式其值为零。
    + **性质4** 行列式中两行对应元素相等，其值为零，即当 
    ![alt text](https://github.com/zhanghaocore/Note_ML/blob/Note_ML_local/mathImg/hanglieshi_nature_4_1.png "n阶行列式的性质3")时有
    
    ![alt text](https://github.com/zhanghaocore/Note_ML/blob/Note_ML_local/mathImg/hanglieshi_nature_4.png "n阶行列式的性质4")
    + **推论2** 行列式中两行对应元素成比例，其值为零
    + **性质5** 在行行列式中，把某行各元素分别乘非零常数k，再加到另一行的对应元素上，行列式的值不变（简称：对行列式做倍加行变换，其值不变），即：
    ![alt text](https://github.com/zhanghaocore/Note_ML/blob/Note_ML_local/mathImg/hanglieshi_nature_5.png "n阶行列式的性质5")
    + **性质6** （反对称性质） 行列式的两行对换，行列式的值反号。
    + **性质7** 行列式某行的元素乘另一行对应元素的代数余子式之和等于零，即：
    ![alt text](https://github.com/zhanghaocore/Note_ML/blob/Note_ML_local/mathImg/hanglieshi_nature_7.png "n阶行列式的性质7")
+ **克拉默(Cramer)法则**
    + **定义** n个未知量n个方程的线性方程组，在系数行列式不等于零时的行列式解法，通常称为**克拉默(Cramer)法则**
+ **矩阵**
    + **定义**如果两个矩阵A和B的行数和列数分别相等，且各对应的元素也相等，就称A和B相等，计作:A=B。
    +  **矩阵的加法** 设A和B行数和列数分别相等，则A+B等于A和B对应元素的加和后所得的矩阵。
        1. 交换律：A+B=B+A
        2. 结合律：(A+B)+C=A+(B+C)
        3. 零矩阵满足：A+0=A,其中0是与A同型的零矩阵
        4. A-B=A+(-B)
    +  **矩阵的数量乘法（简称数乘）**
        + **定义** 设k是数域F中的任意一个数,规定：
            ![alt text](https://github.com/zhanghaocore/Note_ML/blob/Note_ML_local/mathImg/matrix_dingyi_2.4.png "矩阵数乘定义")

        并称这个矩阵为k与A的**数量乘积**

        + **数量乘法的运算律**
            1. 1A=A
            2. (kl)A=k(lA)
            3. (k+l)A=kA+lA
            4. k(A+B)=kA+kB
    + **矩阵的乘法**
        + **定义** 设A是一个 m X n 矩阵，B是一个 n X s 矩阵，即
        ![alt text](https://github.com/zhanghaocore/Note_ML/blob/Note_ML_local/mathImg/matrix_dingyi_2.5.png "矩阵乘法定义")
        + **矩阵运算律**
            1. 结合律(AB)C=A(BC)
            2. 数乘结合律k(AB)=(kA)B=A(kB),其中k是数
            3. 左分配率A(B+C)=AB+AC
               右分配率(B+C)A=BA+CA
        + **单位矩阵** 主对角线全为1，其余元素全为零的n阶矩阵，称为n阶单位矩阵(简称单位矩阵)，记作I_{n}或I或E;
        + **数量矩阵** 主对角线全为非零数k，其余元素全为零的n阶矩阵，称为n阶数量矩阵，计作kI_{n}或kI或kE。
        + **对角矩阵** 非主对角元皆为零的n阶矩阵称为n阶对角矩阵（简称对角阵），计作^
        + **上三角矩阵和下三角矩阵**
        + **行列式乘积** 设A,B是两个n阶矩阵,则乘积AB的行列式等 于 A 和 B 的行列式的乘积 , 即|AB|=|A||B| .









