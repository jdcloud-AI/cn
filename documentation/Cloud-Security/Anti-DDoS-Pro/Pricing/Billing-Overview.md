# 计费概述

## 计费项
京东云IP高防的计费项包括：保底防护、弹性防护、业务带宽。

### 保底防护
IP高防提供的固定防御能力，包括固定的攻击防护峰值（Gbps）和CC防护峰值（QPS），包年包月计费。
保底防护，根据所选线路的不同，价格也不同。线路可选择电信、电信+联通、电信+联通+移动线路。

### 弹性防护
弹性防护是指实际攻击流量超过保底的防护能力后，提供的扩展的DDoS防护能力，包括DDoS攻击防护峰值（Gbps）和CC防护峰值（QPS）的扩展。
弹性防护可升配可降配，若攻击流量未超过保底防护的防护峰值，则不收取费用。

### 业务带宽
指非 DDoS 攻击状态下的正常业务消耗带宽，单位为Mbps。默认赠送100Mbps，可根据需要购买更大的业务带宽。

## 付费方式
### 预付费
包括保底防护+业务带宽，按统一的包年/包月方式计费，只可升级，不可降级。
### 后付费
弹性防护部分按日计费，按照前一日实际发生的，超出保底DDoS防护能力（Gbps）或者CC防护能力（QPS）的攻击峰值取较大的计费区间计算，
生成后付费账单。
若攻击未超过保底防护防御峰值，则弹性防护不收费。


## 续费规则
包年包月续费：延长IP高防实例的到期时长。续费时间段为1个月~9个月、1年、2年、3年。如您在到期前续费，则新订单的开始时间为原订单的到期时间。如您在到期后续费，则新订单的开始时间为续费当天；
批量续费：对多个IP高防实例进行批量续费处理，根据用户所选续费时长，延长选中的资源使用时长。


## 欠费/到期说明
### 包年包月
实例到期后，计费状态会被标记为到期状态，IP高防服务将降级为2G的基础防护能力。如7天内未续费，则在7天后实例会被删除，同时该实例的所有数据配置也会被删除，实例数据不能恢复。
若在7天内及时续费，则续费后保底带宽防护能力和弹性防护能力可正常使用。当您的IP高防实例到期前，京东云会向您发送邮件、短信提醒，请您注意查看并及时续费；当您的IP高防实例到期后，会向您发送邮件和短信通知您的资源已到期，请您务必注意查看通知并及时续费，以免造成不必要的损失。

### 弹性流量后付费
当您的账户中余额加可用于支付该资源的代金券的总和不足以支付上一计费周期（24小时）因弹性流量产生的费用，导致扣款不成功时,您的IP高防实例状态会变为“已欠费”。欠费后IP高防实例的弹性防护能力将被停用，只保留保底防护能力。


## 相关参考

- [计费规则](Billing-Rules.md)
- [价格总览](Price-Overview.md)