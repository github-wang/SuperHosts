## 来源

1. [https://github.com/pexcn/huhamhire-hosts](https://github.com/pexcn/huhamhire-hosts)
2. [https://github.com/txthinking/google-hosts](https://github.com/txthinking/google-hosts)
3. [https://coding.net/u/levi/p/imouto-host/git](https://coding.net/u/levi/p/imouto-host/git)
4. [https://github.com/sundys/android](https://github.com/sundys/android)


## 使用

在Linux下，使用cat命令合并，当然也可以直接下载[`hosts`](https://raw.githubusercontent.com/pexcn/SuperHosts/master/hosts)文件，替换到系统的相应位置。

使用cat命令合并：
```
cat localhost huhamhire-hosts txthinking-hosts imouto-hosts sundys-hosts > hosts
```
或者
```
cat localhost *-hosts > hosts
```
