# Group-6
# 大數據的統計與分析-做出股票分析圖
Final project of Computation for Physics
# Members
* Steven Chang, flagged guy.<br />
* Yu Chuan, 87.<br />
* Chia Chun, baseballman.<br />
* poly, popopopopopo.<br />
* KID Chen, Kaitō Kiddo.<br />
# Goal
Become wealthy men
# Schedule
5/3 & 5/10 收集資料<br />
5/17 & 5/24 畫K線、成交量<br />
5/31 & 6/7 畫KD值線<br />
# Fen gong
Steven Chang & Chia Chun ： 成交量做圖<br />
Yu Chuan & poly & KID Chen ： K線做圖<br />
All ： 畫KD值線
# Plugin
talib<br />
Tushare ： 引入網路股市數據<br />
matplotlib.pyplot ： 繪圖工具<br />
matplotlib.finance<br />
pandas ： 畫圖工具<br />
Stockstats ： 提供KD值公式<br />
# 操作
data = ts.get_k_data('輸入股號', index=True, start='輸入起始年-月-日', end='輸入結束年-月-日')
