SIP_0012_PCV_UPDATE.md
### 提案目的
- 进一步提高协议治理能力，提高sFUND资产的使用率。升级sFUND为协议控制资产(Protocol Controlled Value，PCV) 
 
### 优化方案：
1.    允许sFUND接入Vaults(SOLO/HFI/EDC/COINWIND)，提高相应资产的复用率。
2.    扩展董事会增发部分分配实现动态调整。黑洞基金获取比例由固定5%提升为5% ×(1+K)且最高为40%；K为连续增发次数，直至某日董事会结算时TWAP<0.95重置K为0。
3.    扩展董事会通缩机制实现动态调整。PCV资产回购门槛从固定0.95调整为(0.95-0.05×L)且最低为0.05；L为连续通缩次数，直至某日董事会结算时TWAP>1.05重置为0；SHARE增发回购门槛从固定0.85调整为(0.85-0.05×L)且最低为0.05；L为连续通缩次数，直至某日董事会结算时TWAP>1.05重置为0；
4.    取消新球开放流动性门槛，提高无损挖矿阶段黑洞基金释放数量，从100枚提升至500枚；释放周期从1天延长至5天。
 