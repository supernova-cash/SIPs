SIP_007_SHARESWAP_ADJUSTMENT.md
### 提案目的
- HT价格和NEO的价格飙涨，导致sHT/HT和sNEO/pNEO的TWAP被动下水从而引起SHARE增发。因此建议提高弹性稳定币增发SHARE回购相关资产的阈值并降低数量。提高SHARE抵抗价格波动的能力。

### 优化方案：
- 除sCASH星球外，其余星球的ShareSwap触发条件由TWAP低于0.95调整为0.85，且释放SHARE数量为该星球已释放SHARE数量的1%。