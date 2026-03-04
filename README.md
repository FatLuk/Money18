# Money18更新記錄

[30-1-2026]

原始版本

移除Cookie功能 [載入FG.html後,再上Ellis/Eric.html會導致買入價、股數 錯誤]

[2-2-2026]

(Ellis) 1810更改為1347

[2-2-2026]

(FG) 9988更改為1347
(Eric) 1810更改為1347

[25-2-2026]

(FG Eric Ellis)加入最高價、最低價, 移除代碼loadOrder();「卡片排序」功能

刪除function renderStock中的最後更新時間,保持整潔
document.getElementById('stime'+prefix).textContent="最後更新時間: "+data['API_'+key].stimeNoformat;

[4-3-2026]
(FG Eric Ellis)加入股票註解<!-- 股票1 香港交易所(0388.HK) --> <!-- 股票2 華虹半導體(1347.HK) --> <!-- 股票3 中國平安(2318.HK) --> <!-- 股票4 中國人壽(2628.HK) --> <!-- 股票5 小米集團－W (1810.HK) -->
(Test)單一股票 阿里巴巴－W (9988.HK)
