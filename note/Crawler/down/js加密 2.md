# js(javascript)加密
- 利用js对本地信息进行加密后发送给服务器
- 破解原理:
  - 因为在本地也就是浏览器上进行加密,所以我们既知道明文又知道密文.
  - 所以我们可以自己调用js新型破解
  - [例子](../program/js_encryption.py)
# 明文与密文
- 什么是加密:
  - 在密码学中，加密（英语：Encryption）是将明文信息改变为难以读取的密文内容，使之不可读的过程。只有拥有解密方法的对象，经由解密过程，才能将密文还原为正常可读的内容。
  - js加密的原理:
    - 将所需字符加入一随机字符串(salt:盐)后,通过加密算法后,得到加密字符串.
    - 可以通过字典的方式将键值互换进行破解(如果字符不太长)
    -
