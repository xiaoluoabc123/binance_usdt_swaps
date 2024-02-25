{

'robot1': {

    'start': 0, #0为关闭，1为开启
    'strategy':'pullback_trading', #策略名称
    'symbol': 'PHB/USDT:USDT', #品种名称
    'period':'3m', #周期
    'leverage': 20, #杠杆
    'multiple': 4, #下单倍数，初始1U
    'direct': 1, #指定交易方向，0为多空，1为多，-1为空
    'pr_type': 1, #止盈类型：1为亏损加设定止盈率，2为单止盈不叠加亏损，3为移动止盈
    'prbull': 8, #多头止盈率
    'prbear': 8, #空头止盈率
    'activationRate': 3, #移动止盈触发盈利率
    'callbackRate': 1, #移动止盈触发止盈回撤率
    'st_type': 1, #止损类型，0为不止损，1，为策略止损，3为固定止损
    'st_times': 4, #最大止损次数
    'st_rate': 1.5, #固定止损率
    'add_pos': 0, #加仓，0为不加仓，大于0为加仓倍数，初始为1U
    'add_rate': 0.2, #加仓线，为止损线正向叠加率
    'add_loss': 0, #亏损次数以上叠加
    'matin': 0, #开启叠加马丁
    'm_type': 1, #叠加马丁类型 1为总计数叠加，2为多空分别计算叠加
    'm_loss': 6, #叠加马丁最高亏算次数
    'm_muti': 1.5, #叠加马丁下单倍数
    'm_lever': 3, #叠加马丁每层下单次数
    'breakeven': 99, #保本退出，即在指定亏损次数后根据亏损额自动生成止盈位置
    'del_record': 1, #删除记录，建议策略开始时设置为1
    'pullback_trading':{
    }, #回踩买入
    'upswing_trend':{
    }, #回升买入
    'trend_track':{    
    }, #强趋势追踪
    'manual':{
    'buy_pri': 0, #手动买多价
    'sell_pri': 0, #手动卖空价
    }, #手动策略相关参数
    'grid_trading':{ 
    'grid_deep': 4, # 网格深度
    'grid_rate': 1, #网格每次加仓间隔率
    'g_add_type': 1,  #网格加仓类型：1为固定加仓，2为倍数加仓
    'grid_mult': 1, #倍数马丁加仓率
    }, #网格交易
    
    },

'robot2': {

    'start': 1, #0为关闭，1为开启
    'strategy':'pullback_trading', #策略名称
    'symbol': 'GAL/USDT:USDT', #品种名称
    'period':'3m', #周期
    'leverage': 20, #杠杆
    'multiple': 4, #下单倍数，初始1U
    'direct': 1, #指定交易方向，0为多空，1为多，-1为空
    'pr_type': 1, #止盈类型：1为亏损加设定止盈率，2为单止盈不叠加亏损，3为移动止盈
    'prbull': 6, #多头止盈率
    'prbear': 4, #空头止盈率
    'activationRate': 3, #移动止盈触发盈利率
    'callbackRate': 1, #移动止盈触发止盈回撤率
    'st_type': 1, #止损类型，0为不止损，1，为策略止损，3为固定止损
    'st_times': 99, #最大止损次数
    'st_rate': 1.5, #固定止损率
    'add_pos': 4, #加仓，0为不加仓，大于0为加仓倍数，初始为1U
    'add_rate': 0.2, #加仓线，为止损线正向叠加率
    'add_loss': 0, #亏损次数以上叠加
    'matin': 0, #开启叠加马丁
    'm_type': 1, #叠加马丁类型 1为总计数叠加，2为多空分别计算叠加
    'm_loss': 6, #叠加马丁最高亏算次数
    'm_muti': 1.5, #叠加马丁下单倍数
    'm_lever': 3, #叠加马丁每层下单次数
    'breakeven': 99, #保本退出，即在指定亏损次数后根据亏损额自动生成止盈位置
    'del_record': 1, #删除记录，建议策略开始时设置为1
    'pullback_trading':{
    }, #回踩买入
    'upswing_trend':{
    }, #回升买入
    'trend_track':{    
    }, #强趋势追踪
    'manual':{
    'buy_pri': 0, #手动买多价
    'sell_pri': 0, #手动卖空价
    }, #手动策略相关参数
    'grid_trading':{ 
    'grid_deep': 4, # 网格深度
    'grid_rate': 1, #网格每次加仓间隔率
    'g_add_type': 1,  #网格加仓类型：1为固定加仓，2为倍数加仓
    'grid_mult': 1, #倍数马丁加仓率
    }, #网格交易
    },

'robot3': {

    'start': 1, #0为关闭，1为开启
    'strategy':'pullback_trading', #策略名称
    'symbol': 'GLM/USDT:USDT', #品种名称
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
    'st_times': 99, #最大止损次数
    'st_rate': 1.5, #固定止损率
    'add_pos': 0, #加仓，0为不加仓，大于0为加仓倍数，初始为1U
    'add_rate': 0.2, #加仓线，为止损线正向叠加率
    'add_loss': 0, #亏损次数以上叠加
    'matin': 0, #开启叠加马丁
    'm_type': 1, #叠加马丁类型 1为总计数叠加，2为多空分别计算叠加
    'm_loss': 6, #叠加马丁最高亏算次数
    'm_muti': 1.5, #叠加马丁下单倍数
    'm_lever': 3, #叠加马丁每层下单次数
    'breakeven': 99, #保本退出，即在指定亏损次数后根据亏损额自动生成止盈位置
    'del_record': 1, #删除记录，建议策略开始时设置为1
    'pullback_trading':{
    }, #回踩买入
    'upswing_trend':{
    }, #回升买入
    'trend_track':{    
    }, #强趋势追踪
    'manual':{
    'buy_pri': 0, #手动买多价
    'sell_pri': 0, #手动卖空价
    }, #手动策略相关参数
    'grid_trading':{ 
    'grid_deep': 4, # 网格深度
    'grid_rate': 1, #网格每次加仓间隔率
    'g_add_type': 1,  #网格加仓类型：1为固定加仓，2为倍数加仓
    'grid_mult': 1, #倍数马丁加仓率
    }, #网格交易
    },

'robot4': {

    'start': 1, #0为关闭，1为开启
    'strategy':'grid_trading', #策略名称
    'symbol': 'RLC/USDT:USDT', #品种名称
    'period':'3m', #周期
    'leverage': 20, #杠杆
    'multiple': 1, #下单倍数，初始1U
    'direct': 1, #指定交易方向，0为多空，1为多，-1为空
    'pr_type': 1, #止盈类型：1为亏损加设定止盈率，2为单止盈不叠加亏损，3为移动止盈
    'prbull': 5, #多头止盈率
    'prbear': 4, #空头止盈率
    'activationRate': 3, #移动止盈触发盈利率
    'callbackRate': 1, #移动止盈触发止盈回撤率
    'st_type': 3, #止损类型，0为不止损，1，为策略止损，3为固定止损
    'st_times': 99, #最大止损次数
    'st_rate': 6, #固定止损率
    'add_pos': 0, #加仓，0为不加仓，大于0为加仓倍数，初始为1U
    'add_rate': 0.2, #加仓线，为止损线正向叠加率
    'add_loss': 0, #亏损次数以上叠加
    'matin': 0, #开启叠加马丁
    'm_type': 1, #叠加马丁类型 1为总计数叠加，2为多空分别计算叠加
    'm_loss': 6, #叠加马丁最高亏算次数
    'm_muti': 1.5, #叠加马丁下单倍数
    'm_lever': 3, #叠加马丁每层下单次数
    'breakeven': 99, #保本退出，即在指定亏损次数后根据亏损额自动生成止盈位置
    'del_record': 1, #删除记录，建议策略开始时设置为1
    'pullback_trading':{
    }, #回踩买入
    'upswing_trend':{
    }, #回升买入
    'trend_track':{    
    }, #强趋势追踪
    'manual':{
    'buy_pri': 0, #手动买多价
    'sell_pri': 0, #手动卖空价
    }, #手动策略相关参数
    'grid_trading':{ 
    'grid_deep': 4, # 网格深度
    'grid_rate': 5, #网格每次加仓间隔率
    'g_add_type': 1,  #网格加仓类型：1为固定加仓，2为倍数加仓
    'grid_mult': 1, #倍数马丁加仓率
    }, #网格交易
    },

'robot5': {

    'start': 1, #0为关闭，1为开启
    'strategy':'trend_track', #策略名称
    'symbol': '1000LUNC/USDT:USDT', #品种名称
    'period':'3m', #周期
    'leverage': 20, #杠杆
    'multiple': 4, #下单倍数，初始1U
    'direct': 1, #指定交易方向，0为多空，1为多，-1为空
    'pr_type': 1, #止盈类型：1为亏损加设定止盈率，2为单止盈不叠加亏损，3为移动止盈
    'prbull': 10, #多头止盈率
    'prbear': 10, #空头止盈率
    'activationRate': 3, #移动止盈触发盈利率
    'callbackRate': 1, #移动止盈触发止盈回撤率
    'st_type': 1, #止损类型，0为不止损，1，为策略止损，3为固定止损
    'st_times': 4, #最大止损次数
    'st_rate': 1.5, #固定止损率
    'add_pos': 4, #加仓，0为不加仓，大于0为加仓倍数，初始为1U
    'add_rate': 0.2, #加仓线，为止损线正向叠加率
    'add_loss': 0, #亏损次数以上叠加
    'matin': 0, #开启叠加马丁
    'm_type': 1, #叠加马丁类型 1为总计数叠加，2为多空分别计算叠加
    'm_loss': 6, #叠加马丁最高亏算次数
    'm_muti': 1.5, #叠加马丁下单倍数
    'm_lever': 3, #叠加马丁每层下单次数
    'breakeven': 99, #保本退出，即在指定亏损次数后根据亏损额自动生成止盈位置
    'del_record': 1, #删除记录，建议策略开始时设置为1
    'pullback_trading':{
    }, #回踩买入
    'upswing_trend':{
    }, #回升买入
    'trend_track':{    
    }, #强趋势追踪
    'manual':{
    'buy_pri': 0, #手动买多价
    'sell_pri': 0, #手动卖空价
    }, #手动策略相关参数
    'grid_trading':{ 
    'grid_deep': 4, # 网格深度
    'grid_rate': 1, #网格每次加仓间隔率
    'g_add_type': 1,  #网格加仓类型：1为固定加仓，2为倍数加仓
    'grid_mult': 1, #倍数马丁加仓率
    }, #网格交易
    },

'robot6': {

    'start': 1, #0为关闭，1为开启
    'strategy':'trend_track', #策略名称
    'symbol': 'SPELL/USDT:USDT', #品种名称
    'period':'3m', #周期
    'leverage': 20, #杠杆
    'multiple': 4, #下单倍数，初始1U
    'direct': 1, #指定交易方向，0为多空，1为多，-1为空
    'pr_type': 1, #止盈类型：1为亏损加设定止盈率，2为单止盈不叠加亏损，3为移动止盈
    'prbull': 10, #多头止盈率
    'prbear': 10, #空头止盈率
    'activationRate': 3, #移动止盈触发盈利率
    'callbackRate': 1, #移动止盈触发止盈回撤率
    'st_type': 1, #止损类型，0为不止损，1，为策略止损，3为固定止损
    'st_times': 4, #最大止损次数
    'st_rate': 1.5, #固定止损率
    'add_pos': 4, #加仓，0为不加仓，大于0为加仓倍数，初始为1U
    'add_rate': 0.2, #加仓线，为止损线正向叠加率
    'add_loss': 0, #亏损次数以上叠加
    'matin': 0, #开启叠加马丁
    'm_type': 1, #叠加马丁类型 1为总计数叠加，2为多空分别计算叠加
    'm_loss': 6, #叠加马丁最高亏算次数
    'm_muti': 1.5, #叠加马丁下单倍数
    'm_lever': 3, #叠加马丁每层下单次数
    'breakeven': 99, #保本退出，即在指定亏损次数后根据亏损额自动生成止盈位置
    'del_record': 1, #删除记录，建议策略开始时设置为1
    'pullback_trading':{
    }, #回踩买入
    'upswing_trend':{
    }, #回升买入
    'trend_track':{    
    }, #强趋势追踪
    'manual':{
    'buy_pri': 0, #手动买多价
    'sell_pri': 0, #手动卖空价
    }, #手动策略相关参数
    'grid_trading':{ 
    'grid_deep': 4, # 网格深度
    'grid_rate': 1, #网格每次加仓间隔率
    'g_add_type': 1,  #网格加仓类型：1为固定加仓，2为倍数加仓
    'grid_mult': 1, #倍数马丁加仓率
    }, #网格交易
    },
  
'robot7': {

    'start': 1, #0为关闭，1为开启
    'strategy':'trend_track', #策略名称
    'symbol': 'XVG/USDT:USDT', #品种名称
    'period':'3m', #周期
    'leverage': 20, #杠杆
    'multiple': 4, #下单倍数，初始1U
    'direct': 1, #指定交易方向，0为多空，1为多，-1为空
    'pr_type': 1, #止盈类型：1为亏损加设定止盈率，2为单止盈不叠加亏损，3为移动止盈
    'prbull': 10, #多头止盈率
    'prbear': 10, #空头止盈率
    'activationRate': 3, #移动止盈触发盈利率
    'callbackRate': 1, #移动止盈触发止盈回撤率
    'st_type': 1, #止损类型，0为不止损，1，为策略止损，3为固定止损
    'st_times': 4, #最大止损次数
    'st_rate': 1.5, #固定止损率
    'add_pos': 4, #加仓，0为不加仓，大于0为加仓倍数，初始为1U
    'add_rate': 0.2, #加仓线，为止损线正向叠加率
    'add_loss': 0, #亏损次数以上叠加
    'matin': 0, #开启叠加马丁
    'm_type': 1, #叠加马丁类型 1为总计数叠加，2为多空分别计算叠加
    'm_loss': 6, #叠加马丁最高亏算次数
    'm_muti': 1.5, #叠加马丁下单倍数
    'm_lever': 3, #叠加马丁每层下单次数
    'breakeven': 99, #保本退出，即在指定亏损次数后根据亏损额自动生成止盈位置
    'del_record': 1, #删除记录，建议策略开始时设置为1
    'pullback_trading':{
    }, #回踩买入
    'upswing_trend':{
    }, #回升买入
    'trend_track':{    
    }, #强趋势追踪
    'manual':{
    'buy_pri': 0, #手动买多价
    'sell_pri': 0, #手动卖空价
    }, #手动策略相关参数
    'grid_trading':{ 
    'grid_deep': 4, # 网格深度
    'grid_rate': 1, #网格每次加仓间隔率
    'g_add_type': 1,  #网格加仓类型：1为固定加仓，2为倍数加仓
    'grid_mult': 1, #倍数马丁加仓率
    }, #网格交易
    },
  
'robot8': {

    'start': 0, #0为关闭，1为开启
    'strategy':'trend_track', #策略名称
    'symbol': 'GLM/USDT:USDT', #品种名称
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
    'st_times': 99, #最大止损次数
    'st_rate': 1.5, #固定止损率
    'add_pos': 0, #加仓，0为不加仓，大于0为加仓倍数，初始为1U
    'add_rate': 0.2, #加仓线，为止损线正向叠加率
    'add_loss': 0, #亏损次数以上叠加
    'matin': 0, #开启叠加马丁
    'm_type': 1, #叠加马丁类型 1为总计数叠加，2为多空分别计算叠加
    'm_loss': 6, #叠加马丁最高亏算次数
    'm_muti': 1.5, #叠加马丁下单倍数
    'm_lever': 3, #叠加马丁每层下单次数
    'breakeven': 99, #保本退出，即在指定亏损次数后根据亏损额自动生成止盈位置
    'del_record': 1, #删除记录，建议策略开始时设置为1
    'pullback_trading':{
    }, #回踩买入
    'upswing_trend':{
    }, #回升买入
    'trend_track':{    
    }, #强趋势追踪
    'manual':{
    'buy_pri': 0, #手动买多价
    'sell_pri': 0, #手动卖空价
    }, #手动策略相关参数
    'grid_trading':{ 
    'grid_deep': 4, # 网格深度
    'grid_rate': 1, #网格每次加仓间隔率
    'g_add_type': 1,  #网格加仓类型：1为固定加仓，2为倍数加仓
    'grid_mult': 1, #倍数马丁加仓率
    }, #网格交易
    },
  
'robot9': {

    'start': 0, #0为关闭，1为开启
    'strategy':'macd', #策略名称
    'symbol': 'MDT/USDT:USDT', #品种名称
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
    'st_times': 99, #最大止损次数
    'st_rate': 1.5, #固定止损率
    'add_pos': 0, #加仓，0为不加仓，大于0为加仓倍数，初始为1U
    'add_rate': 0.2, #加仓线，为止损线正向叠加率
    'add_loss': 0, #亏损次数以上叠加
    'matin': 0, #开启叠加马丁
    'm_type': 1, #叠加马丁类型 1为总计数叠加，2为多空分别计算叠加
    'm_loss': 6, #叠加马丁最高亏算次数
    'm_muti': 1.5, #叠加马丁下单倍数
    'm_lever': 3, #叠加马丁每层下单次数
    'breakeven': 99, #保本退出，即在指定亏损次数后根据亏损额自动生成止盈位置
    'del_record': 1, #删除记录，建议策略开始时设置为1
    'pullback_trading':{
    }, #回踩买入
    'upswing_trend':{
    }, #回升买入
    'trend_track':{    
    }, #强趋势追踪
    'manual':{
    'buy_pri': 0, #手动买多价
    'sell_pri': 0, #手动卖空价
    }, #手动策略相关参数
    'grid_trading':{ 
    'grid_deep': 4, # 网格深度
    'grid_rate': 1, #网格每次加仓间隔率
    'g_add_type': 1,  #网格加仓类型：1为固定加仓，2为倍数加仓
    'grid_mult': 1, #倍数马丁加仓率
    }, #网格交易
    },
  
'robot10': {

    'start': 0, #0为关闭，1为开启
    'strategy':'macd', #策略名称
    'symbol': 'GTC/USDT:USDT', #品种名称
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
    'st_times': 99, #最大止损次数
    'st_rate': 1.5, #固定止损率
    'add_pos': 0, #加仓，0为不加仓，大于0为加仓倍数，初始为1U
    'add_rate': 0.2, #加仓线，为止损线正向叠加率
    'add_loss': 0, #亏损次数以上叠加
    'matin': 0, #开启叠加马丁
    'm_type': 1, #叠加马丁类型 1为总计数叠加，2为多空分别计算叠加
    'm_loss': 6, #叠加马丁最高亏算次数
    'm_muti': 1.5, #叠加马丁下单倍数
    'm_lever': 3, #叠加马丁每层下单次数
    'breakeven': 99, #保本退出，即在指定亏损次数后根据亏损额自动生成止盈位置
    'del_record': 1, #删除记录，建议策略开始时设置为1
    'pullback_trading':{
    }, #回踩买入
    'upswing_trend':{
    }, #回升买入
    'trend_track':{    
    }, #强趋势追踪
    'manual':{
    'buy_pri': 0, #手动买多价
    'sell_pri': 0, #手动卖空价
    }, #手动策略相关参数
    'grid_trading':{ 
    'grid_deep': 4, # 网格深度
    'grid_rate': 1, #网格每次加仓间隔率
    'g_add_type': 1,  #网格加仓类型：1为固定加仓，2为倍数加仓
    'grid_mult': 1, #倍数马丁加仓率
    }, #网格交易
    },
  
'robot11': {

    'start': 0, #0为关闭，1为开启
    'strategy':'macd', #策略名称
    'symbol': 'GAL/USDT:USDT', #品种名称
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
    'st_times': 99, #最大止损次数
    'st_rate': 1.5, #固定止损率
    'add_pos': 0, #加仓，0为不加仓，大于0为加仓倍数，初始为1U
    'add_rate': 0.2, #加仓线，为止损线正向叠加率
    'add_loss': 0, #亏损次数以上叠加
    'matin': 0, #开启叠加马丁
    'm_type': 1, #叠加马丁类型 1为总计数叠加，2为多空分别计算叠加
    'm_loss': 6, #叠加马丁最高亏算次数
    'm_muti': 1.5, #叠加马丁下单倍数
    'm_lever': 3, #叠加马丁每层下单次数
    'breakeven': 99, #保本退出，即在指定亏损次数后根据亏损额自动生成止盈位置
    'del_record': 1, #删除记录，建议策略开始时设置为1
    'pullback_trading':{
    }, #回踩买入
    'upswing_trend':{
    }, #回升买入
    'trend_track':{    
    }, #强趋势追踪
    'manual':{
    'buy_pri': 0, #手动买多价
    'sell_pri': 0, #手动卖空价
    }, #手动策略相关参数
    'grid_trading':{ 
    'grid_deep': 4, # 网格深度
    'grid_rate': 1, #网格每次加仓间隔率
    'g_add_type': 1,  #网格加仓类型：1为固定加仓，2为倍数加仓
    'grid_mult': 1, #倍数马丁加仓率
    }, #网格交易
    },
  
'robot12': {

    'start': 0, #0为关闭，1为开启
    'strategy':'macd', #策略名称
    'symbol': 'PHB/USDT:USDT', #品种名称
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
    'st_times': 99, #最大止损次数
    'st_rate': 1.5, #固定止损率
    'add_pos': 0, #加仓，0为不加仓，大于0为加仓倍数，初始为1U
    'add_rate': 0.2, #加仓线，为止损线正向叠加率
    'add_loss': 0, #亏损次数以上叠加
    'matin': 0, #开启叠加马丁
    'm_type': 1, #叠加马丁类型 1为总计数叠加，2为多空分别计算叠加
    'm_loss': 6, #叠加马丁最高亏算次数
    'm_muti': 1.5, #叠加马丁下单倍数
    'm_lever': 3, #叠加马丁每层下单次数
    'breakeven': 99, #保本退出，即在指定亏损次数后根据亏损额自动生成止盈位置
    'del_record': 1, #删除记录，建议策略开始时设置为1
    'pullback_trading':{
    }, #回踩买入
    'upswing_trend':{
    }, #回升买入
    'trend_track':{    
    }, #强趋势追踪
    'manual':{
    'buy_pri': 0, #手动买多价
    'sell_pri': 0, #手动卖空价
    }, #手动策略相关参数
    'grid_trading':{ 
    'grid_deep': 4, # 网格深度
    'grid_rate': 1, #网格每次加仓间隔率
    'g_add_type': 1,  #网格加仓类型：1为固定加仓，2为倍数加仓
    'grid_mult': 1, #倍数马丁加仓率
    }, #网格交易
    },
  
'robot13': {

    'start': 0, #0为关闭，1为开启
    'strategy':'macd', #策略名称
    'symbol': 'ALT/USDT:USDT', #品种名称
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
    'st_times': 99, #最大止损次数
    'st_rate': 1.5, #固定止损率
    'add_pos': 0, #加仓，0为不加仓，大于0为加仓倍数，初始为1U
    'add_rate': 0.2, #加仓线，为止损线正向叠加率
    'add_loss': 0, #亏损次数以上叠加
    'matin': 0, #开启叠加马丁
    'm_type': 1, #叠加马丁类型 1为总计数叠加，2为多空分别计算叠加
    'm_loss': 6, #叠加马丁最高亏算次数
    'm_muti': 1.5, #叠加马丁下单倍数
    'm_lever': 3, #叠加马丁每层下单次数
    'breakeven': 99, #保本退出，即在指定亏损次数后根据亏损额自动生成止盈位置
    'del_record': 1, #删除记录，建议策略开始时设置为1
    'pullback_trading':{
    }, #回踩买入
    'upswing_trend':{
    }, #回升买入
    'trend_track':{    
    }, #强趋势追踪
    'manual':{
    'buy_pri': 0, #手动买多价
    'sell_pri': 0, #手动卖空价
    }, #手动策略相关参数
    'grid_trading':{ 
    'grid_deep': 4, # 网格深度
    'grid_rate': 1, #网格每次加仓间隔率
    'g_add_type': 1,  #网格加仓类型：1为固定加仓，2为倍数加仓
    'grid_mult': 1, #倍数马丁加仓率
    }, #网格交易
    },
  
'robot14': {

    'start': 0, #0为关闭，1为开启
    'strategy':'macd', #策略名称
    'symbol': 'LOOM/USDT:USDT', #品种名称
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
    'st_times': 99, #最大止损次数
    'st_rate': 1.5, #固定止损率
    'add_pos': 0, #加仓，0为不加仓，大于0为加仓倍数，初始为1U
    'add_rate': 0.2, #加仓线，为止损线正向叠加率
    'add_loss': 0, #亏损次数以上叠加
    'matin': 0, #开启叠加马丁
    'm_type': 1, #叠加马丁类型 1为总计数叠加，2为多空分别计算叠加
    'm_loss': 6, #叠加马丁最高亏算次数
    'm_muti': 1.5, #叠加马丁下单倍数
    'm_lever': 3, #叠加马丁每层下单次数
    'breakeven': 99, #保本退出，即在指定亏损次数后根据亏损额自动生成止盈位置
    'del_record': 1, #删除记录，建议策略开始时设置为1
    'pullback_trading':{
    }, #回踩买入
    'upswing_trend':{
    }, #回升买入
    'trend_track':{    
    }, #强趋势追踪
    'manual':{
    'buy_pri': 0, #手动买多价
    'sell_pri': 0, #手动卖空价
    }, #手动策略相关参数
    'grid_trading':{ 
    'grid_deep': 4, # 网格深度
    'grid_rate': 1, #网格每次加仓间隔率
    'g_add_type': 1,  #网格加仓类型：1为固定加仓，2为倍数加仓
    'grid_mult': 1, #倍数马丁加仓率
    }, #网格交易
    },
  
'robot15': {

    'start': 0, #0为关闭，1为开启
    'strategy':'trend_track', #策略名称
    'symbol': 'BLUR/USDT:USDT', #品种名称
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
    'st_times': 99, #最大止损次数
    'st_rate': 1.5, #固定止损率
    'add_pos': 0, #加仓，0为不加仓，大于0为加仓倍数，初始为1U
    'add_rate': 0.2, #加仓线，为止损线正向叠加率
    'add_loss': 0, #亏损次数以上叠加
    'matin': 0, #开启叠加马丁
    'm_type': 1, #叠加马丁类型 1为总计数叠加，2为多空分别计算叠加
    'm_loss': 6, #叠加马丁最高亏算次数
    'm_muti': 1.5, #叠加马丁下单倍数
    'm_lever': 3, #叠加马丁每层下单次数
    'breakeven': 99, #保本退出，即在指定亏损次数后根据亏损额自动生成止盈位置
    'del_record': 1, #删除记录，建议策略开始时设置为1
    'pullback_trading':{
    }, #回踩买入
    'upswing_trend':{
    }, #回升买入
    'trend_track':{    
    }, #强趋势追踪
    'manual':{
    'buy_pri': 0, #手动买多价
    'sell_pri': 0, #手动卖空价
    }, #手动策略相关参数
    'grid_trading':{ 
    'grid_deep': 4, # 网格深度
    'grid_rate': 1, #网格每次加仓间隔率
    'g_add_type': 1,  #网格加仓类型：1为固定加仓，2为倍数加仓
    'grid_mult': 1, #倍数马丁加仓率
    }, #网格交易
    
    },
  
'robot16': {
    
    'start': 0, #0为关闭，1为开启
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
    'st_times': 99, #最大止损次数
    'st_rate': 1.5, #固定止损率
    'add_pos': 0, #加仓，0为不加仓，大于0为加仓倍数，初始为1U
    'add_rate': 0.2, #加仓线，为止损线正向叠加率
    'add_loss': 0, #亏损次数以上叠加
    'matin': 0, #开启叠加马丁
    'm_type': 1, #叠加马丁类型 1为总计数叠加，2为多空分别计算叠加
    'm_loss': 6, #叠加马丁最高亏算次数
    'm_muti': 1.5, #叠加马丁下单倍数
    'm_lever': 3, #叠加马丁每层下单次数
    'breakeven': 99, #保本退出，即在指定亏损次数后根据亏损额自动生成止盈位置
    'del_record': 1, #删除记录，建议策略开始时设置为1
    'pullback_trading':{
    }, #回踩买入
    'upswing_trend':{
    }, #回升买入
    'trend_track':{    
    }, #强趋势追踪
    'manual':{
    'buy_pri': 0, #手动买多价
    'sell_pri': 0, #手动卖空价
    }, #手动策略相关参数
    'grid_trading':{ 
    'grid_deep': 4, # 网格深度
    'grid_rate': 1, #网格每次加仓间隔率
    'g_add_type': 1,  #网格加仓类型：1为固定加仓，2为倍数加仓
    'grid_mult': 1, #倍数马丁加仓率
    }, #网格交易
    },
        
}
