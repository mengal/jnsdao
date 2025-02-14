---
sidebar_position: 3
---

import ExtLinkSvg from '/static/img/extlink.svg';

# JNS大事记

### JNS组建JNS DAO

2022年12月6号，Jouleverse-core决定把JNS项目无偿捐赠给社区，组建JNS DAO。捐赠的核心资产包括：
1. JNS的品牌。
2. JNS的合约代码，目前包括：NFT资产合约，治理投票合约。【注1】
3. JNS NFT图形的外观设计。
4. JNS前期拍卖的全部收入。【注2】

- <small>【注1】Jouleverse区块链浏览器相关前端显示代码属于浏览器项目，另有开放方式。</small>
- <small>【注2】收入全部进入社区金库（treasury），是DAO治理的重点。金库合约尚未完成，有待后续开发。</small>

同时，Jouleverse-core决定：
1. 继续无偿提供技术支持（现阶段的社区金库也肯定不足以cover这项工作的开支），直至社区金库有足够的支付能力能够支付该项费用（亦可由其他开发设计人员接手）。
2. 继续无偿提供财务结算和藏品交割的支持，直至Leadership Team的相关工作组可以接手。
3. 继续无偿提供风控的支持，并暂时保留mint的权限，因为要前向对mint的每一个NFT进行合规性的审查，避免政治、文化等方面的风险。后续开发相关风控合约后，再移交该流程。

### JNS DAO 1号提案

2022年12月21号，JNS DAO完成第一次链上民主投票：选举产生了JNS DAO的第一届常务委员会，包括5名委员：@芳芳 @张恩畅 @Koant  @🌱老謝 @楼兰渔夫 。
以22票100%赞成、代表度58.53%获得表决通过✅
（[查看链上记录<ExtLinkSvg />](https://jscan.jnsdao.com/#/jnsvote)）

### JNS DAO 2号提案

2023年2月30号，JNSDAO 2号提案：表决JNSDAO治理程序「三段式投票，两参数表决（赞成率>2/3且代表度>1/2）」
投票结果为：赞成率 100%（24票赞成：0票反对）合格，代表度 40.57%（赞成票代表99个JNS）不合格，未通过❌
（[查看链上记录<ExtLinkSvg />](https://jscan.jnsdao.com/#/jnsvote)）

### JNS DAO 3号提案

2023年3月10号，JNSDAO 3号提案：重新表决确定治理程序「三段式投票、两参数表决」（代表度从1/2降为40%）
以27 票(100％)赞成、代表度43.03%获得表决通过✅
（[查看链上记录<ExtLinkSvg />](https://jscan.jnsdao.com/#/jnsvote)）
确定链上投票通过提案的标准根据两个参数“赞成率”和“代表度”定义如下：
1. 赞成率超过 2/3 即约 66.67% 以上（投票者中，超过2/3多数赞成）
2. 赞成票的代表度超过 2/5 即约 40% 以上（赞成票投票者总共持有超过40%数量的JNS资产）

### JNS DAO 4号提案

2023年4月9号，JNSDAO 4号提案：改进JNS DAO治理机制，选举@koant.j为首任CEO，由其组建LT班子，领衔JNS DAO共治、共建。
以29 票(100％)赞成、代表度41.39%获得表决通过✅
（[查看链上记录<ExtLinkSvg />](https://jscan.jnsdao.com/#/jnsvote)）

### JNS DAO 5号提案

2023年4月23号，JNSDAO 5号提案：表决改进JNS DAO治理机制，提升治理水平和发展效率
以32 票(100％)赞成、代表度47.13%获得表决通过✅
（[查看链上记录<ExtLinkSvg />](https://jscan.jnsdao.com/#/jnsvote)）

### JNS DAO 6号提案

2023年5月2号，JNSDAO 6号提案：@koant.j任命@健康美丽财富David 为市场发展组的组长，@🌱老谢 为市场发展组副组长，@岑云|见路不走 为拍卖组组长，@Menger 为拍卖组副组长
以26票(100%)赞成、代表度41.39获得表决通过✅
（[查看链上记录<ExtLinkSvg />](https://jscan.jnsdao.com/#/jnsvote)）

### JNS DAO 7号提案

2023年7月11号，JNSDAO 7号提案：JNSDAO公众号招募特约撰稿人和荐稿人，长期为JNSDAO公众号提供优质内容，按贡献优质文章内容篇数奖励JNS白名单
以27票(100%)赞成、代表度45.42%获得表决通过✅
（[查看链上记录<ExtLinkSvg />](https://jscan.jnsdao.com/#/jnsvote)）

### JNS铸造合约控制权移交至多签

2023年7月24号:
1. JNS合约的所有权，主要是新域名的铸造权限，已从教链移交给多签合约，完成了进一步的去中心化。目前，教链已不再拥有JNS合约的任何权限。
2. 多签合约相关代码已完成升级开发，兼容NFT协议（包括JNS）。
3. 为JNS DAO部署的多签合约为2/3多签，目前第1签名人为：Koant - JNS DAO现任CEO；第2签名人为：岑云 - JNS DAO拍卖组组长；第3签名人为：教链 - 技术备份。后续可经由JNS DAO治理投票程序变更签名人。
4. JNS拍卖后的铸造和发放将转由第1、2多签人联合操作，指示多签合约在链上执行铸造和发放动作。
5. 教链捐赠出个人持有的JNS域名 GM.j 给JNS DAO，用于绑定该多签合约地址，为其建立抽象账户DID：https://jscan.jnsdao.com/#/did/GM.j （注：GM的含义可以是General Manager总经理，蕴含其拥有JNS铸造执行权的意思）

这次JNS合约的GM抽象账户的建立也验证了一个对JNS重要赋能的可行性：即，我们可以为每一个JNS域名建立一个抽象账户（AA），实现与普通钱包地址（EOA）的分离，并赋予其灵活的单、多人控制权限。
（[查看详情<ExtLinkSvg />](https://mp.weixin.qq.com/s/Up1jXpQKlnjqhDYsoQYuhg)）
