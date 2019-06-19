"""
mutiprocessing TCP流式套接字
登录 name(varchar(32) primary key) password(varchar(32) not null)
一级 函数 登录 注册 退出（break）
注册成功后直接进入二级界面
查单词使用while True 界面1 while True 界面2
查询字典 name word time 新建一个table order by 10
客户端（发请求，展示结果）
服务端（逻辑操作，解决请求）
数据库操作端（操作数据库）
网络搭建
注册
登录
查单词
历史记录

注册： 客户端 R name
"""
"""
import hashlib
import getpass
pwd = getpass.getpass()
print(pwd)

#算法加盐
hash = hashlib.md5("*$#md".encode())
hash.update(pwd.encode()) #算法加密
pwd = hash.hexdigest()  #提取加密后的密码
print(pwd)
"""
