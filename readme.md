java 密码处理
=

原文地址: [来自][]
参考文献: [文献][]

[来自]:https://gist.github.com/jtan189/3804290 "代码来源"
[文献]:http://crackstation.net/hashing-security.htm "文献地址"

如何使用
-

由于全是静态函数, 所以可以直接使用</br>

函数
-
    createHash()可以直接调用来进行哈希的生成, 参数可以是string或char[]</br>
    validatePassword()参数是需要校验的密码, 和比较的哈希值</br>
    getPbkdf2HashLength()获取此哈希值的长度, 在定义数据库类型长度的时候进行参考</br>
    