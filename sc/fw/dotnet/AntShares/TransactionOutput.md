# TransactionOutput 类

用来表示交易输出的数据结构。一个交易输出有三个字段，转账的是哪种资产，转账到哪个地址，转了多少金额。

命名空间：[AntShares.SmartContract.Framework.Services.AntShares](../AntShares.md)

程序集：AntShares.SmartContract.Framework

## 语法

```c#
public class TransactionOutput : IApiInterface
```

## 属性

|                                          | 名称                                       | 说明     |
| ---------------------------------------- | ---------------------------------------- | ------ |
| ![](https://i-msdn.sec.s-msft.com/dynimg/IC74937.jpeg) | [AssetId](TransactionOutput/AssetId.md)  | 获得资产ID |
| ![](https://i-msdn.sec.s-msft.com/dynimg/IC74937.jpeg) | [ScriptHash](TransactionOutput/ScriptHash.md) | 获得脚本散列 |
| ![](https://i-msdn.sec.s-msft.com/dynimg/IC74937.jpeg) | [Value](TransactionOutput/Value.md)      | 获得交易金额 |
