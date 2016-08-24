# GTMBase64
---
由于 r258833095/GTMBase64 项目已停止更新，为了方便大家的使用，提交了此版本，如果侵权，请通知本人进行移除

优化:

1. 支持ARC
2. 修改md5_base64方法实现 (原方法在处理\0问题上存在问题，有关思路见 http://qiufeng.me/md5)


使用方法:

1）将 GTMBase64 文件夹添加至iOS项目中

2）在使用GTMBase64的地方 #import "GTMBase64.h" 引入头文件
