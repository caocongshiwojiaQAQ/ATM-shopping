# ATM-shopping
https://www.cnblogs.com/kermitjam

ATM + 购物车
1、需求分析

2、设计程序以及程序的架构
    设计程序的好处:
        - 扩展性强
        - 逻辑清晰

3、分任务开发

4、测试
    黑盒:

    白盒：
        对程序性能的测试

5、上线运行

# 项目需求如下:
- 信用卡额度15000或自定义 ---> 注册
- 实现购物商城，买东西加入购物车，调用信用卡接口结账 ---> 购物车功能、支付
- 可以提现，手续费5% ---> 提现  * 1.05
- 支持多账户登录 ---> 登录
- 支持账户间转账 ---> 转账
- 记录消费流水 ---> 记录流水
- 提供还款接口 ---> 还款
- ATM记录操作日志 ---> 记录日志
- 提供管理接口，包括添加账户、用户额度，冻结账户等... ---> 添加账户、冻结账户
- 用户认证功能 ---> 使用装饰器实现认证功能


# 给用户选择的功能
1、注册
2、登录
3、查看余额
4、提现
5、转账
6、还款
7、查看流水
8、购物车
9、查看购物车



# 设计项目目录结构
- ATM
　　- conf 配置文件文件夹
　　　　- setting.py

　　- lib 公共方法文件夹
　　　　- common.py　　公共方法文件

　　- interface 接口层文件夹
　　　　- user.py　　用户接口文件
　　　　- shop.py　　购物接口文件
　　　　- bank.py　　银行接口文件

　　- core 用户功能文件夹
　　　　- src.py　　视图文件

　　- db 数据处理层文件夹
　　　　- db_handler.py　　数据处理功能文件

　　- log　　日志存放目录

　　- start.py　　程序的入口文件，启动文件

　　- readme　　程序的说明文件






