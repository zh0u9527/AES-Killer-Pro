# AES-Killer-Pro
AES KillerPro 工具对AES-Killer工具的一些功能增强优化，主要如下：
- AES加解密填充方式，原始只支持PKCS5，现支持一下方式：
  - AES/CBC/NoPadding
  - AES/CBC/PKCS5Padding
  - AES/CBC/PKCS7Padding
  - AES/ECB/NoPadding
  - AES/ECB/PKCS5Padding
  - AES/ECB/PKCS7Padding
- 请求体/响应体字符替换
  - 有些网址会将加密的请求体字符串使用引号引起来，这时便可以使用字符替换功能进行替换；可以同时多对多的字符替换，注意：当需要替换的字符个数大于替换的字符长度时，这时的替换是使用替换字符的最后一个字符来替换需要替换的字符。
- 明文/密文加解密

AES-KillerPro：
![image](https://github.com/zh0u9527/AES-Killer-Pro/assets/92257130/8be47538-6271-40b9-aa27-ec5ff6cb79f2)

AES-Killer：
![image](https://github.com/zh0u9527/AES-Killer-Pro/assets/92257130/828e173d-0ac3-4339-9ae9-2e0a407adede)
