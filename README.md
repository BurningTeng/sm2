### SM2算法介绍
SM2是国家密码管理局于2010年12月17日发布的椭圆曲线公钥密码算法.


SM2算法和RSA算法都是公钥密码算法，SM2算法是一种更先进安全的算法，在我们国家商用密码体系中被用来替换RSA算法。

随着密码技术和计算机技术的发展，目前常用的1024位RSA算法面临严重的安全威胁，我们国家密码管理部门经过研究，决定采用SM2椭圆曲线算法替换RSA算法。


SM2性能更优更安全：密码复杂度高、处理速度快、机器性能消耗更小
|     | SM2  | RSA|
|  ----  | ----  |  ---  |
| 算法结构  | 基本椭圆曲线（ECC） |基于特殊的可逆模幂运算 |
| 计算复杂度  | 完全指数级 |亚指数级|
|存储空间|192-256bit| 2048-4096bit|
|秘钥生成速度|较RSA算法快百倍以上|慢|
|解密加密速度|较快|一般|
###  代码参考链接
[C#实现SM2国密加密](https://www.cnblogs.com/valu/p/12842778.html)
###  创建一个repository
```shell
echo "# sm2" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M master
git remote add origin https://github.com/BurningTeng/sm2.git
git push -u origin master
```
### push一个已经存在的repository
```shell
git remote add origin https://github.com/BurningTeng/sm2.git
git branch -M master
git push -u origin master
```