{

'robot1': {

    'start': 1, #0为关闭，1为开启
    'strategy':'macd', #策略名称
    'symbol': 'ACH/USDT:USDT', #品种名称
    'period':'3m', #周期
    'leverage': 20, #杠杆
    'multiple': 4, #下单倍数，初始1U
    'direct': 1, #指定交易方向，0为多空，1为多，-1为空
    'pr_type': 1, #止盈类型：1为亏损加设定止盈率，2为单止盈不叠加亏损，3为移动止盈
    'prbull': 4, #多头止盈率
    'prbear': 4, #空头止盈率
    'activationRate': 3, #移动止盈触发盈利率
    'callbackRate': 1, #移动止盈触发止盈回撤率
    'st_type': 1, #止损类型，0为不止损，1，为策略止损，3为固定止损
    'st_rate': 1.5, #固定止损率
    'add_pos': 0, #加仓，0为不加仓，大于0为加仓倍数，初始为1U
    'add_rate': 0.2, #加仓线，为止损线正向叠加率
    'add_loss': 0, #亏损次数以上叠加
    'matin': 0, #开启马丁
    'm_type': 1, #马丁类型 1为总计数叠加，2为多空分别计算叠加
    'm_loss': 6, #最高马丁亏算次数
    'm_muti': 1.5, #马丁下单倍数
    'm_lever': 3, #马丁每层下单次数
    'breakeven': 99, #保本退出，即在指定亏损次数后根据亏损额自动生成止盈位置
    'del_record': 1, #删除记录，建议策略开始时设置为1
    'macd':{
    }, #macd策略相关参数
    'rsi':{
    }, #rsi策略相关参数
    'manual':{
    'buy_pri': 0, #手动买多价
    'sell_pri': 0, #手动卖空价
    
    }, #手动策略相关参数
},

'robot2': {

    'start': 1, #0为关闭，1为开启
    'strategy':'macd', #策略名称
    'symbol': 'ACH/USDT:USDT', #品种名称
    'period':'3m', #周期
    'leverage': 20, #杠杆
    'multiple': 4, #下单倍数，初始1U
    'direct': 1, #指定交易方向，0为多空，1为多，-1为空
    'pr_type': 1, #止盈类型：1为亏损加设定止盈率，2为单止盈不叠加亏损，3为移动止盈
    'prbull': 4, #多头止盈率
    'prbear': 4, #空头止盈率
    'activationRate': 3, #移动止盈触发盈利率
    'callbackRate': 1, #移动止盈触发止盈回撤率
    'st_type': 1, #止损类型，0为不止损，1，为策略止损，3为固定止损
    'st_rate': 1.5, #固定止损率
    'add_pos': 0, #加仓，0为不加仓，大于0为加仓倍数，初始为1U
    'add_rate': 0.2, #加仓线，为止损线正向叠加率
    'add_loss': 0, #亏损次数以上叠加
    'matin': 0, #开启马丁
    'm_type': 1, #马丁类型 1为总计数叠加，2为多空分别计算叠加
    'm_loss': 6, #最高马丁亏算次数
    'm_muti': 1.5, #马丁下单倍数
    'm_lever': 3, #马丁每层下单次数
    'breakeven': 99, #保本退出，即在指定亏损次数后根据亏损额自动生成止盈位置
    'del_record': 1, #删除记录，建议策略开始时设置为1
    'macd':{
    }, #macd策略相关参数
    'rsi':{
    }, #rsi策略相关参数
    'manual':{
    'buy_pri': 0, #手动买多价
    'sell_pri': 0, #手动卖空价
    
    }, #手动策略相关参数 
},

}
