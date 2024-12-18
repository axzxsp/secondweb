---
title: 数模mooc笔记
date: 2024-12-18 19:42:02
tags: 
mathjax: true
categories: 笔记
---

## NIM游戏（数论模型）
### 游戏描述
 - 现有n堆硬币，每堆数量一定
 - 两人轮流取硬币，每次只能从其中一堆中取，每次取至少一枚
 - 取到最后一枚硬币的一方获胜
 - 
![](/images/shumo/{F459A725-C94B-4CAE-80F2-5D68DF4AF36E}.png)
### 必胜策略
![](/images/shumo/{B7C42A83-B096-46CE-A3C2-D9A3ACC857F5}.png)

![](/images/shumo/{D5118C31-B131-4AFF-9B27-03F3B39D8F84}.png)
![](/images/shumo/{F13FCC29-A03B-4132-8D7B-B3125847686A}.png)
![](/images/shumo/{39DF4506-6968-4B7E-9010-CEBEA0F660C4}.png)

---

---
## 秘密共享（数论与代数模型）
### 描述：
- 安全门上安装多把锁，所有锁同时打开时安全门才能打开。每人拥有部分锁的钥匙，每把钥匙只能打开一把锁，一把锁可以配多把钥匙。
### 组合方法
![](/images/shumo/{0B15E9D2-7CD6-4F2B-9996-A86B80286822}.png)
#### 推广
![](/images/shumo/{B39C0851-D6D1-4219-87B2-E2D265F506EC}.png)

![](/images/shumo/{A16A3211-4658-4100-9E7C-5FF06016F31E}.png)

### Shamir门限机制
#### 密码学
- 秘密共享（secret sharing）
	将秘密分成若干份，分发给不同的用户。用户特定子集共同提供各自的份额，才能重构初始秘密。
- 门限机制（threshold scheme）
	在n人之间共享秘密，其中任意$t\leqslant n$个人可求出秘密，任意t-1个人无法求出秘密。
#### Shamir门限机制（t，n）
![](/images/shumo/{35D46893-3423-40ED-8240-4C688C8D6439}.png)
![](/images/shumo/{3CDF4B70-C05D-433B-90A6-61739958862B}.png)
![](/images/shumo/{5FD906E0-AC0F-4A93-B2FB-AA687E7FC144}.png)
what↑
### 中国剩余定理
![](/images/shumo/{276FF077-EEF1-4657-9798-275BDD6019C2}.png)

![](/images/shumo/{2F92E3F1-B3F8-4A72-BEFC-D25A057B07D5}.png)

![](/images/shumo/{E9E8123A-10A8-415A-9708-3E4D75CEDAE9}.png)
![](/images/shumo/{AEC3D6EA-2EEB-46E4-B820-B0BF8A8CD9C1}.png)
### Asmuth-Bloom门限机制

![](/images/shumo/{16F10B58-9867-4B6C-A3B8-A8168F80892C}.png)


![](/images/shumo/{AA96E039-C37B-425A-9C0B-7DBF4463FADD}.png)

![](/images/shumo/{298174B2-C737-49D3-9B07-FC87B054FE95}.png)


![](/images/shumo/{BA1A76D2-C0B8-49AF-AF43-2E30D6EE788D}.png)



## 蛛网模型与Cournot模型(函数与数列模型）

### 商品价格与均衡

![](/images/shumo/{9BE159FC-C756-49F4-97BE-47B681FF5AA4}.png)

![](/images/shumo/{6E8AADEB-E084-48AA-A6C6-D1DF9CD21D62}.png)
![](/images/shumo/{088E5512-A225-4E8D-A236-39EEEB431445}.png)


### 蛛网模型
![](/images/shumo/{918E7141-7BDE-47C0-9F63-07600A44F11C}.png)

![](/images/shumo/{3C7D90AD-3B50-4DC9-9FC6-6CE7603A63BD}.png)


![](/images/shumo/{65608E1C-25F3-489B-AD65-DC596979035F}.png)


![](/images/shumo/{D7A3A814-2BC0-4AD6-8AE0-897CEF40E6C1}.png)


![](/images/shumo/{D1C3EF55-5E9B-44ED-B79B-BA1D363B13D0}.png)
即收敛要求商品价格上涨时，供给量的增加量，应小于需求量的减小量
![](/images/shumo/{6D2E8BEA-A2D0-4F97-BB77-64A8F8AFB818}.png)

![](/images/shumo/{F2E229E4-8D7C-4CC4-8261-154E8E553553}.png)


### 差分方程
![](/images/shumo/{F147A38A-22C3-45E9-BF94-852A1745A5E6}.png)
![](/images/shumo/{2C0FBF33-92C7-4596-ABC4-B56C7C128EA4}.png)
![](/images/shumo/{3D2D38F3-7206-4F64-9A5E-537CC881D09A}.png)
#### 差分
![](/images/shumo/{FBF02288-D44D-483B-B03F-1AC3425E291D}.png)


![](/images/shumo/{2B1A306A-DBCD-4AD1-B793-305A7B9C996B}.png)
#### 含有未知函数的有限差分的方程
- $F(n,y_n,\Delta y_n,\cdots ,\Delta ^m y_n)=0$
- $F(n,y_n, y_{n+1},\cdots , y_{n+m})=0$
![](/images/shumo/{7A51CA36-3F09-4F98-A276-1FB9DF905983}.png)![](/images/shumo/{DE3E1ED2-BBD9-4939-A199-17EEDC72A0D7}.png)



![](/images/shumo/{E9827AB5-57D7-4FE8-88B7-AA80B62A0E5C}.png)

![](/images/shumo/{A7CCCB5A-FF86-4A9F-B9FD-E90241B8C7D2}.png)
![](/images/shumo/{7CA87E04-7D27-4E8B-BBA2-A1E385394269}.png)





### Cournot模型(古诺模型)

![](/images/shumo/{EAF1C675-22DB-4171-8D17-652F81CD86E5}.png)


![](/images/shumo/{DABE2099-9A21-4F33-9FC6-D848AAB2EE0E}.png)
![](/images/shumo/{19FEA00E-6ED5-4B99-BFC4-59672096138D}.png)



![](/images/shumo/{1A5F7549-38D1-414D-9CDB-9C57CCE2081B}.png)
![](/images/shumo/{5358B197-FA5A-4481-99B8-44C660649903}.png)

![](/images/shumo/{84CDB064-7CFC-47C0-AA90-28984F4040EF}.png)

![](/images/shumo/{D2679962-35DA-478E-B6E8-1509BAA00C9C}.png)




![](/images/shumo/{10DD3EFD-0964-49AE-8B17-C50A478423E5}.png)

![](/images/shumo/{42118FBD-B736-413F-9836-28E38C8BFE38}.png)

![](/images/shumo/{94E83A8F-DC3F-4362-A9AF-3192C5124B31}.png)
![](/images/shumo/{2F4B45AA-403B-4C28-9D55-044FD8A197DE}.png)



![](/images/shumo/{1B7F4083-2998-4E19-96AE-84F0076F437C}.png)

![](/images/shumo/{2B412619-C1C2-4452-95B1-B7F351E67DFC}.png)







## Bertrand模型

![](/images/shumo/{512922C6-8E59-424B-B81F-406AA33012CE}.png)![](/images/shumo/{BB61C58E-A40D-4F2A-8752-758E5B4A0825}.png)

![](/images/shumo/{552B636D-F883-4AB3-B21D-D28AC0E18D1A}.png)

![](/images/shumo/{DA4185E0-04AD-47FE-80AB-2508039BEEED}.png)
![](/images/shumo/{414DC046-7CB6-47B1-B8D4-EC3964CB4CDE}.png)

![](/images/shumo/{52901F18-6802-4148-AC19-3777075F2103}.png)


![](/images/shumo/{077A5245-3D79-468C-A46F-2ABE436C6060}.png)



![](/images/shumo/{686498D5-B225-48AC-959D-CF9FE8958603}.png)




![](/images/shumo/{06B72980-F82D-4CE9-BC6C-24AC54B94877}.png)





![](/images/shumo/{39F99E43-C86F-4616-997F-E464E1D8AA26}.png)




![](/images/shumo/{6F0F9A33-5056-4FE3-8390-A7568EAF876F}.png)


## Monty Hall问题（概率模型）
### 疾病检测
- 疾病监测方法的性能指标
	- 灵敏度（sensitivity）p 患病者被检测为阳性的概率
	- 特异度（specificity）q 未患病者被检测为阴性（negative）的概率
	- 两者不能相互替代
- 被检测为阳性的情况下患病的概率
	记A为患病，B为检测结果为阳性：灵敏度$p=P(B|A)$,特异度$q=P(\overline B |\overline A)$
	设疾病的发病率为r
	$$P(A|B)=\frac{P(B|A)P(A)}{P(B|A)P(A)+P(B|\overline A )P(\overline A)}=\frac{pr}{pr+(1-q)(1-r)}$$
	e.g. r=0.005,p=0.95,q=0.99
	$P(A|B)= \frac{95}{294}\approx 0.323$
![](/images/shumo/{9249A3C0-C98D-41CC-9881-77E0CE548169}.png)


### Monty Hall问题的基本形式(蒙蒂霍尔问题)
观众参与的竞猜游戏
####  补充设定：
- 假设主持人知道汽车所在的位置
- 竞猜者选择后，主持人打开的门既不是竞猜者选择的，也不是后面有汽车的。
- 有时可能有两扇门符合上面的要求，比如竞猜者初次选择的门后就是汽车，那么另外两扇门后都是山羊。主持人以相等的概率选择其中一扇打开。

原问题中，汽车的位置是事先固定的。竞猜者在没有任何信息的情况下，选择三扇门的概率都是1/3。

#### 等价假设
- 假设竞猜者初次选择1号门，汽车位于1、2、3号门后的概率相同。
- 如果汽车在1号门后，主持人以相等的概率打开2号门或3号门中的其中一扇
- 汽车在2号门后，主持人只能打开3号门
- 汽车在3号门后，主持人只能打开2号门
- 若竞猜者不改变选择，则获得汽车的概率为1/3
- 若竞猜者改变选择，则获得汽车的概率为2/3
- 竞猜者获得汽车的概率是原来的两倍
![](/images/shumo/{DCF9CD6B-3967-40F7-8801-FA69DE3A7C5C}.png)

#### 数学推导
1. 假设竞猜者初次选择1号门
	记 $C_i$为事件“汽车位于$i$号门后’
	$P(C_1)= P(C_2)= P(C_3)=\frac{1}{3}$
2. 假设主持人打开2号门
	记$M$为事件“主持人打开2号门”
	汽车在1号门后 $P(M|C_1)=\frac{1}{2}$
	汽车在2号门后 $P(M|C_2)=0$
	汽车在3号门后 $P(M|C_3)=1$
3. 主持人打开2号门这一事件发生情况下，获得汽车这一事件的条件概率
   - 若竞猜者不改变选择，获得汽车的概率为
   $$P(C_1|M)=\frac{P(M|C_1)P(C_1)}{P(M|C_1)P(C_1)+P(M|C_2)P(C_2)+P(M|C_3)P(C_3)}=\frac{1}{3}$$
    - 若竞猜者改变选择，选择三号门，获得汽车的概率为
    $$P(C_3|M)=\frac{P(M|C_3)P(C_3)}{P(M|C_1)P(C_1)+P(M|C_2)P(C_2)+P(M|C_3)P(C_3)}=\frac{2}{3}$$
- 汽车在不同门后，主持人打开2号门的条件概率是不同的:
	- 汽车在1号门后，主持人只有一半的可能打开2号门
    - 汽车在3号门后，主持人一定打开2号门



### Monty Hall问题的推广
#### 另一种假设
1. 竞猜者选择之后，主持人以相同的概率打开其中的一扇。
	1. 主持人打开的门后是汽车
		游戏以另一种方式结束，不在我们的讨论范围之内
	2. 主持人打开的门后是山羊
		记$M$为事件“主持人选择打开2号门，且门后是一头山羊”
		汽车在1号门后 $P(M|C_1)=\frac{1}{2}$
		汽车在2号门后 $P(M|C_2)=0$
		汽车在3号门后 $P(M|C_3)=\frac{1}{2}$
2. 若竞猜者不改变选择，获得汽车的概率为
   $$P(C_1|M)=\frac{P(M|C_1)P(C_1)}{P(M|C_1)P(C_1)+P(M|C_2)P(C_2)+P(M|C_3)P(C_3)}=\frac{1}{2}$$
3. 若竞猜者改变选择，选择三号门，获得汽车的概率为
    $$P(C_3|M)=\frac{P(M|C_3)P(C_3)}{P(M|C_1)P(C_1)+P(M|C_2)P(C_2)+P(M|C_3)P(C_3)}=\frac{1}{2}$$
- 主持人不知道汽车在哪里，他的行为就不会提供有用的信息

#### Monty Hall问题的变形
1. 多扇门的蒙蒂霍尔问题
	- 有 $n$扇道具门，其中一扇门后置有一辆汽车，其他 $n-1$扇门后各置有一头山羊
	- 当至少有三扇门还未打开时，竞猜者选择其中一扇未打开的门，主持人以相同概率打开竞猜者未选择且后面是山羊的门中的任意一扇，并允许竞猜者改变之前的选择。继续上述过程直至只有两扇门还未打开
2. 多扇门、多辆车的蒙蒂霍尔问题
	-  有$n$扇道具门，其中k扇门后各置有一辆汽车，其他$n-k$扇门后各置有一头山羊
	- 竞猜者选择其中一扇门后，主持人以相同概率打开了其他$n-1$扇门中的 $m$扇，$1≤m≤n-2$，其中j扇门后各有一辆汽车，$m-j$扇门后各有一头山羊
 3. 多扇门、多种奖品的蒙蒂霍尔问题
    - 有 $n$ 扇道具门，其中$n_i$扇门后各置有价值为$v_i$的奖品，$i=1,…,m$
	- 竞猜者选择其中一扇门后，主持人以相同概率打开了其他$n-1$扇门中的一扇，并允许竞猜者改变之前的选择。

## 安全观演（几何模型）
### 观演距离问题
#### 安全观演问题条件
广场某处正在进行一场露天表演，若干人先后到达附近并选择一个地点观看表演
##### 观众选择地点的要求:
- 与舞台中心的距离不小于L
- 与之前到达的任一观众的距离不小于r
- 在满足上述要求的情况下，观众选择与舞台中心距离最近的某个点
![](/images/shumo/{9C7677E8-51F8-4906-979E-1BCB51F7409C}.png)

##### 观众选择地点的方式:
- 有引导:观众在工作人员引导下到达满足要求的地点
- 无引导:观众自行选择满足要求的地点

##### 观演距离
- 求第n个到达的观众与舞台中心的距离$d_n$的估计

#### 观演距离
![](/images/shumo/1732594182202.png)
![](/images/shumo/{DB13048F-FD8F-409B-9CE3-CEC1118DE3C8}.png)



![](/images/shumo/{B75C8D2B-1C83-43F1-A3A3-4376458AAF35}.png)




### 无遮观演
 
![](/images/shumo/{A2BF8816-C891-4794-8166-182F337A9876}.png)
![](/images/shumo/{B9800693-6259-49FD-B53E-E99155E49636}.png)

![](/images/shumo/{670DBD09-FFE9-4186-9E37-B3528E592C7F}.png)
![](/images/shumo/{CD88456A-02BB-4493-927E-332DAA72EC94}.png)
![](/images/shumo/{89150F55-5CD0-43C8-B3A4-42096BE04C6B}.png)

