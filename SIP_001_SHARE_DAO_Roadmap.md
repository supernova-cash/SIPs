SIP_001_SHARE_DAO_Roadmap.md

中文/CHINESE

## 超新星宇宙议会(SHARE-DAO)治理框架


### 宇宙治理
超新星宇宙议会将于2021年4月2日下午4点正式开启宇宙治理。所有SHARE的持有者可以通过捐赠SHARE来可获取投票权证vSHARE和收益凭证sSHARE。并可参与创世提案(SIP-001 SHARE-DAO Roadmap)投票。目前提案表决分为 支持/反对 两个选项，所有持有vSHARE的用户均可参与投票。投票结束后，支持选项得票数超过反对选项得票数，即表示通过，否则表示被拒绝。

### SIP提案
任何人都可以在社区内广泛征集意见并充分讨论形成提案，在指定仓库 (https://github.com/SuperNova-CASH/SIPs) 打开一个 Pull Request 来提交提案内容。在第一个月，由 SuperNova核心团队负责筛选提案并提交投票。一个月后，将由宇宙议员进行提案筛选并提交投票。
### 宇宙议员
捐赠SHARE所获取的收益凭证sSHARE可以被永久得质押在董事会合约中而不能被取出，同时也将获得该星球议员的竞选资格，在改选日(每个月第一天)质押sSHARE数量排名前列的用户地址将自动获得成为该星球议员的资格，不同星球根据其产出SHARE总量的不同，所能被委派的议员数量也有所不同，初始议员名额分配如下：
- sCASH/sHT/sNEO星球3名
- sMDX/sFIL/sDOT星球2名
- sFILDA/sNULS/sCAN/sFLM星球1名
备注：随着更低级别星球的诞生，高级别星球也将获得更多的议员名额
### 宇宙税
宇宙间资产转换时，被转入资产的宇宙将根据流通数量、平均价格收取一定比例的资产作为税收，以维持不同宇宙间的经济平衡。宇宙税分配原则如下：
- 5% 公链开发基金：用于支持公链生态发展
- 5% 创世治理激励：用于创世治理提案参与者的激励
- 5% 宇宙议员激励：用于宇宙议员的激励
- 10% 宇宙治理基金：用于已通过提案中的市场和运营支出
- 25% 宇宙治理激励：用于参与SIP议案投票者的激励
- 50% 宇宙金库基金：为宇宙间的资产转换提供基础流动性并获取增值收益，从而激励宇宙治理和发展 

### 合约升级
为了实现上述需求，需要对部分合约进行升级，涉及合约包括：
- ShareBoardroom_sCASH 合约地址：0x95Ceea71AD465C86b61C642154617C5b5DD1a07d
- ShareBoardroom_sHT 合约地址：0x47E09a5316dF2b0499A55c3eD2C0e5A648e258C0
- ShareBoardroom_sNEO 合约地址：0xdA9157AeD7e4EE16C6270e96D6d96203c4178D04
- LPBoardroom_sCASH 合约地址：0xb4daC8D70f0e0255039d328C1Bff2cD3Cfb46150
- LPBoardroom_sHT 合约地址：0x8A30eAe49358b25F67aFf4d21Bc35b9D64A29Da4
- LPBoardroom_sNEO 合约地址：0x0DE652114636B1fD7810829Db6d9ee5185BbeFCd
- Treasury_sCASH 合约地址：0xA0459009Ce9b414541ABA9496C47a691A42Ad285
- Treasury_sHT 合约地址：0x7b1B89875F11C32C988E8E9FbCCB6B66E612CB6D
- Treasury_sNEO 合约地址：0x6840f577e02B3C59519A5bD43c85d0F672E37e11
升级内容：
1.添加sSHARE质押入口
2.增加质押倒计时
在SIP-001投票通过后，将会对原合约进行升级和部署。特别注意的是，因为原ShareBoardroom合约对质押SHARE的用户有72小时的锁仓期，LPBoradroom合约对质押LP的用户有24小时的锁仓期，请大家合理安排质押时间和顺序。








ENGLISH/英文

## SHARE-DAO Governance Framework


### Governance
The Supernova Congress will officially start at 8:00（UTC+0）on April 2nd 2021. All SHARE holders can donate SHARE to get vSHARE and sSHARE, and can participate in the genesis proposal ( SIP-001 SHARE-DAO Roadmap) voting. At present proposal is divided into voting support / oppose these options, all holders of vSHAREs can vote. After the voting is over, if the number of votes for the support option exceeds the number of votes for the opposition option, it means that it is passed, otherwise it means it is rejected.
 
### SIP
Anyone can collect a wide range of opinion within the community, and a full discussion of the proposal form(SuperNova Improvement Proposal,SIP), Pull Request in https://github.com/SuperNova-CASH/SIPs to submit proposals. In the first month, the SuperNova Core team is responsible for screening proposals and submit votes . A month later, it will be a proposal screening by the senators of planets and submiting votes (DAO).
 
### Senator
The income certificate sSHARE obtained by donating SHARE can be permanently pledged in the board of directors contract and cannot be taken out. At the same time, it will also be eligible for election as a member of the planet. The number of pledges of sSHARE on the re-election day (the first day of each month ) highest ranks of user address will automatically be eligible to become a member of the planet. According to the total amount of SHARE produced by different planets , the number of members that can be appointed is also different . The initial allocation of members is as follows:
- sCASH/sHT/sNEO Planet 3 Senators 
- sMDX /sFIL/sDOT Planet 2 Senators
- sFILDA/sNULS/sCAN/sFLM Planet 1 Senator
Remark: With the birth of lower-level planets, higher-level planets will also get more senators.
### Universe tax
When assets are transferred between universes, the universe transferred into assets will collect a certain percentage of assets as taxes (fees) based on the circulating quantity and average price (TWAP) to maintain the economic balance between different universes. 
The principle of universe tax/fee distribution is as follows:
- 5% public chain development fund : used to support the ecological development of the public chain
- 5% Creation management incentive : a proposal for the creation of governance participants incentive
- 5% Cosmos Senator Incentive : Used for Cosmos Senator's incentive
- 10% Universe Governance Fund : Used for market and operating expenses in approved proposals
- 25 % of the universe management incentive : to participate SIP motion voters incentives
- 50% Universe Treasury Fund: Provide basic liquidity and gain value-added income for asset conversion between the universe, thereby encouraging the governance and development of the universe
 
### Contract Upgrade
In order to achieve the above requirements, some contracts need to be upgraded. The involved contracts include:
- ShareBoardroom_sCASH contract address: 0x95Ceea71AD465C86b61C642154617C5b5DD1a07d
- ShareBoardroom_sHT contract address: 0x47E09a5316dF2b0499A55c3eD2C0e5A648e258C0
- ShareBoardroom_sNEO contract address: 0xdA9157AeD7e4EE16C6270e96D6d96203c4178D04
- LPBoardroom_sCASH contract address: 0xb4daC8D70f0e0255039d328C1Bff2cD3Cfb46150
- LPBoardroom_sHT contract address: 0x8A30eAe49358b25F67aFf4d21Bc35b9D64A29Da4
- LPBoardroom_sNEO contract address: 0x0DE652114636B1fD7810829Db6d9ee5185BbeFCd
- Treasury_sCASH contract address: 0xA0459009Ce9b414541ABA9496C47a691A42Ad285
- Treasury_sHT contract address: 0x7b1B89875F11C32C988E8E9FbCCB6B66E612CB6D
- Treasury_sNEO contract address: 0x6840f577e02B3C59519A5bD43c85d0F672E37e11
Upgrade Content:
1.	Add sSHARE pledge entry
2.	Increase pledge countdown
After the SIP- 001 vote is passed, new contracts will be deployed. Special attention: ShareBoardroom Contract has a 72-hour lock period, and LP Boardroom has a 24-hour period Lock, please arrange pledged time and sequence. 
