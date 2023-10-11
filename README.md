# cracker
 
私钥碰撞, 学习使用, 请勿用于其它用途.


用法 https://www.youtube.com/watch?v=75NIxCBut2I&t=45s


# 私钥碰撞 - 平时电脑也是开着的, 极低的概率,
# 思路:  钱包 助记词 私钥 随机 生成钱包
#1, 随机生成eth钱包
#2, 查询余额, 转帐纪录
#  eth, bsc,
#3, 有则存下来, 且发到指定邮箱
#

# 私钥碰撞
# 随机生成私钥, 万一不小心这个钱包地址有币则把私钥, 钱包余额发到指定邮箱. 有了私钥, 你要怎么做就是你的事了, 我的建议是通知钱包主人
# 默认查询 eth, bsc这两条链的余额以及是否有交易纪录

配置文件  config.yml


# 发送到你指定的邮箱, 可以用QQ邮箱来接收
# 可到qq邮箱生成一个授权码, 

`
mail_to: "xxxx@qq.com"

smtp:
  host: "smtp.qq.com"
  port: 587
  username: "xxxxxx@qq.com"     # 你的邮箱全名
  password: ""                  # qq邮箱的授权码 hotmail邮箱则是正常的登录密码

`


