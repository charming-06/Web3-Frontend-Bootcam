- Github ID: charming-06

- Openbuild Username: charming-06

- ERC20 钱包地址: 0xaDAdC83516AF6c24B231EC7224438c1dDD06Da3f

### 个人介绍
休息了一年，学习三个月也不过分吧

### 学习记录
#### 20240604
1、鲁棒性：简单来说就是对特定的条件才进行处理，其他未考虑的情况不做处理，避免系统出现问题，保持系统稳定性


#### 20240605
1、web3 api和web2区别：
    1）rpc url代理
    2）登录（钱包）非独立系统登录，一个global的统一登录认证系统，这也导致登录很慢，我猜openbuild也是使用了统一登录？因为巨慢
    3）链接合约（合约地址和ABI）
    4）去中心化的区块链存储和私有服务器的存储
2、每一个节点就是一个rpc服务器，我们发送请求也是发送到rpc代理服务器，相当于web3的一个后台服务器。只不过web3的是去中心化的，任何人都可以访问的
3、欧易3钱包支持更多的虚拟币、可以导入钱包。

问题：
3、智能合约和rpc代理服务器的关系是什么？


#### 20240605
1、变量定义的类型有：local、state、global
2、变量的存储位置：storage、memory、calldata
3、常量的类型：constant、immutable
4、函数可见性的关键字：
    public 全部可见
    private 定义了该方法的类可见
    internal 只可以内部调用的方法
    external 只可以外部调用的方法

5、interface合约，只能声明方法，但是不能编写方法，它必须是可以继承的，所以要使用external关键字
6、导入合约 import ‘本地地址’ or  import '互联网地址'
7、错误处理关键字
    require：条件判断
    revert：回滚操作
    assert：一定要满足某条件


### React学习过程：
1、React 组件是常规的 JavaScript 函数，但 组件的名称必须以大写字母开头，否则它们将无法运行！
2、允许你在 JavaScript 中嵌入使用标签，这种语法被称为 JSX。实际上是 JavaScript！
3、如果你的标签和 return 关键字不在同一行，则必须把它包裹在一对括号中。没有括号包裹的话，任何在 return 下一行的代码都 将被忽略！
4、react中组件之间的传值可以怎么做？1）事件派发之后另一个组件去获取，单向数据流

