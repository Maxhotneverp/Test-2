# Ladder（云梯）
<pre>
<h2>制度框架</h2>
	基本介绍
		一：基本信息
                   初始总量：3000万（交易及转账代币总量持续减少)
                   参与者买入扣除10%，卖出亦扣除10%其中，买入扣除的10%由买入者买入时直接扣除，
                   卖出扣除的10%不为交易者承担计入大盘总流通筹码的定向数据通缩 *其中5%永久销毁，
                   5%进入奖金池进入奖金池的5%将放大为100%，分为三个奖金池
                       1.尾单博弈奖金池：35%
                       2.团队持续开发和运营：5%
                       3.持币分红奖金池：60% （持币分红奖金池里50%每天分给持币24小时的用户，如遇交易量萎缩，
                       不足每日交易代币数量不足当前流通额5%则将剩余50%回馈至持币分红池子）

<h2>通缩燃烧规则说明</h2>
		
                       每交易一笔将燃烧10%代币
                       例：某某购买1000枚代币，实际到账900枚代币（其中5%代币=50枚永久销毁，另外5%代币=50枚进入奖金池）
                       ⚠️：其中买入扣除的10%买入者买入时直接扣除，卖出扣除的10%不为交易者承担计入大盘总流通筹码的定向数据通缩 
 

<h2>代币供给体系说明</h2>
                       SWAP底仓：30000000  
                       弹性供给仓：无上限！   
<h4>弹性供给仓：</h4>
                       （Z为持币基准持仓数值，P为价格，T为结算时间）
                       T1 = Z
                       T2 = Z* {（P2-P1）/ P1} / 10 /30
                       ⚠️：{（P2-P1）/ P1} 部分只取值《=10%部分，溢出部分不计算！
<h4>尾单博弈:</h4>
		       1. 若当前时间与上次尾单博弈时间的间隔超过 60 分钟，则进行派奖:
                       当前奖励名单中，最后 1 人可获得奖池中 10% 的代币，除最后 1 人外，其余9位每人可获得奖池中 2% 的代币
		       2. 如果此时奖励名单人 数>10 人，则剔除最后10人以外所有地址。
		       • 初始为 （30000000-  burn）*1/5000 + 3√Supply*1/10
		       • 任意用户参与尾单博弈时，要求数额增加  :
		       {（30000000-  burn）*1/5000 + 3√Supply*1/10}*(1+0.02)^X
		       • 该要求数额的上限是
		       {（30000000-  burn）*1/5000 + 3√Supply*1/10}*(1+0.02)^X 代币 
		       <=  
		       {（30000000-  burn）*1/1000 + 3√Supply*1/10}
		       • 每次派奖时结束后，要求数额将还原到:
 		       （30000000-  burn）*1/5000 + 3√Supply*1/10
			
<h5>分红要求</h5>
	               销毁分红
		              （30000000-  burn）*1/1500 + 3√Supply*1/10
	               弹性供给仓
		              （30000000-  burn）*1/1500 + 3√Supply*1/10
</pre>
