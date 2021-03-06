# dongbei 语言考试小抄

## 变量

```
老张是活雷锋。  # 定义变量。初始值：啥也不是。
老张装二。  # 老张 = 2
削老张。  # 老张 = 啥也不是
老王是活雷锋。
老王装仨。  # 老王 = 3
老张装老王。  # 引用变量。老张 = 3
```

## 群众

```
张家庄都是活雷锋。  # 张家庄是个群众变量。初始值是[]。
张家庄来了个二加三。  # 张家庄现在 = [5]。
张家庄来了个“大”。   # 张家庄现在 = [5, '大']
唠唠：张家庄有几个坑。  # 2
唠唠：张家庄的老大。  # 第一个人（5）。
唠唠：张家庄的老（三减一）。  # 第二个人（'大'）。
唠唠：张家庄的老幺。  # 最后一个人（'大'）。
李家村都是活雷锋。  # 李家村也是个群众变量。初始值是[]。
李家村来了个三。  # 李家村现在 = [3]。
李家村来了个张家庄。  # 群众的一个元素本身可以是群众。李家村现在 = [3, [5, '大']]。
唠唠：李家村的老幺的老大。  # 5。
削张家庄。  # 张家庄现在啥也不是。
```

## 运算

```
老张走走。  # 老张 += 1
老张走两步。  # 老张 += 2
老张稍稍。  # 老张 -= 1
老张稍三步。  # 老张 -= 3
老张装老王加二。  # 老张 = 老王 + 2
老张装（老张减三）除以五乘老王。  # 老张 = (老张 - 3)/5*老王
老张装 老张齐整整地除以老王 # 老张 = (老张 / 老王)，只留整数部分
```

## 比较

```
老王比5大
7加二比老刘小
老张跟老王一样一样的
老李跟250不是一样一样的
老刘啥也不是
```

## 打印

```
唠唠：“唉呀妈呀”。  # 打印字符串常量。
唠唠：老王。  # 打印变量的值。
唠唠：老王比老张大。  # 打印表达式的值。
唠唠：“老王是”、老王。  # 打印两个表达式的并置。
```

## 条件

```
寻思：老王比老张大？
要行咧就唠唠：“老王！”。
要不行咧就唠唠：“老张！”。
```

## 循环

```
老王从1到10磨叽：
  唠唠：老王。
磨叽完了！

老张在张家庄磨叽：
  唠唠：老张。
磨叽完了。
```

## 组合

```
寻思：老王比老张大？
要行咧就开整：
  唠唠：“老王！”。
  唠唠：“你好美！”。
整完了。
```
## 套路

```
【阶乘】（那啥）咋整：  # 定义套路 阶乘，有一个参数 那啥。
  寻思：那啥比一小？ # 需要自推吗？
  要行咧就 滚犊子吧 一。  # 返回值1。
  要不行咧就 滚犊子吧 那啥乘整【阶乘】（那啥减一）。  # 需要。返回自推结果。
整完了。  # 定义结束。

唠唠：整【阶乘】（五）！  # 使用套路
```

## 帮衬

```
翠花，上 math。  # 导入 python math 模块。
唠唠：整 math.factorial（五）。  # 整个 python 套路。
```
