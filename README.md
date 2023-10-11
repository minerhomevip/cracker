# cracker
 
## 私钥碰撞, 学习使用, 请勿用于其它用途.

用法 https://www.youtube.com/watch?v=75NIxCBut2I&t=45s


###  平时电脑开着也是开着, 就让它跑着玩, 万一中彩票呢.适用于win, ubuntu20
###  随机生成私钥, 万一不小心这个钱包地址有币则把私钥, 钱包余额发到指定邮箱. 有了私钥, 你要怎么做就是你的事了, 我的建议是通知钱包主人
###  默认查询 eth, bsc这两条链的余额以及是否有交易纪录
#### 1, 随机生成eth钱包
#### 2, 查询余额(eth, bsc两条链), 转帐纪录
#### 3, 有则存下来, 且发到指定邮箱




配置文件  config.yml

~
mail_to: "xxxx@qq.com"

smtp:
  host: "smtp.qq.com"
  port: 587
  username: "xxxxxx@qq.com"     # 你的邮箱全名
  password: ""                  # qq邮箱的授权码 hotmail邮箱则是正常的登录密码

~


