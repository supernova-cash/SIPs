SIP_0015_SUPERNOVA_UPDATE_SCHEDULE.md
### 提案目的
- 为了确保SHARE合约升级过程平稳有序的进行，确保已有用户持有的SHARE能够平稳有序进行。目前筹备的升级时间表如下：

### 提案内容：
- 新SHARE代币特性：
   + 每笔转账/交易将被收取5%的费用，其中3%用于SHARE持有者奖励；2%用于添加MDEX上的SHARE/wHT流动性深度(永久锁定)；
- 具体操作包括：
   + 在DEX通过SHARE-USDT-LP或SHARE-wHT-LP买入：5%
   + 在DEX通过SHARE-USDT-LP或SHARE-wHT-LP卖出：5%
   + 在DEX上组建SHARE-USDT-LP或SHARE-wHT-LP：5%(仅计算SHARE部分
   + 在DEX上移除SHARE-USDT-LP或SHARE-wHT-LP：5%(仅计算SHARE部分)
   + 在DEX通过其他SHARE相关LP买入：5%(当前版本暂时设置为0)
   + 在DEX通过其他SHARE相关LP卖出：5%(当前版本暂时设置为0)
   + 在DEX上组建其他SHARE相关LP：5%(当前版本暂时设置为0)
   + 在DEX上移除其他SHARE相关LP：5%(当前版本暂时设置为0)
   + 从矿池领取SHARE收益：5%(当前版本暂时设置为0)
   + 在董事会质押SHARE：5%(当前版本暂时设置为0)
   + 从董事会领取SHARE：5%(当前版本暂时设置为0)

- SHARE持有者奖励发放地址包括：
   + 持有SHARE未进行质押的用户地址
   + SHARE-USDT-LP和SHARE-wHT-LP的合约地址(在移除流动性时分给用户)
   + 其他SHARE相关LP的合约地址(当前版本为0)
   + 董事会质押SHARE的合约地址(当前版本为0)

- SHARE代币置换时间：
   + 新SHARE合约发布时间：5月5日16:00 (UTC+8)
   + SHARE置换合约开放时间：5月5日16:00 (UTC+8)-5月7日（UTC+8）
   + 用户可以在宇宙议会完成旧SHARE代币置换成新SHARE代币的操作。

- 原有合约升级：
   + 董事会合约升级时间：5月6日16:00 (UTC+8)
   + 黑洞合约升级时间：5月6日16:00 (UTC+8)
   + 议会合约升级时间：5月6日16:00 (UTC+8)
   + 虫洞合约升级时间：5月6日16:00(UTC+8)
   + 即自5月6日16:00开始，所有SHARE相关合约均仅支持新版本SHARE代币。