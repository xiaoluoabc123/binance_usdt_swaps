{

'robot1': {

    'start': 1, #0为关闭，1为开启
    'strategy':'pullback_trading', #策略名称
    'symbol': 'ALICE/USDT:USDT', #品种名称
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
    'add_pos': 4, #加仓，0为不加仓，大于0为加仓倍数，初始为1U
    'add_rate': 0.2, #加仓线，为止损线正向叠加率
    'add_loss': 0, #亏损次数以上叠加
    'matin': 0, #开启叠加马丁
    'm_type': 1, #叠加马丁类型 1为总计数叠加，2为多空分别计算叠加
    'm_loss': 6, #叠加马丁最高亏算次数
    'm_muti': 1.5, #叠加马丁下单倍数
    'm_lever': 3, #叠加马丁每层下单次数
    'breakeven': 5, #保本退出，即在指定亏损次数后根据亏损额自动生成止盈位置
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
    'or_type': 2, # 1，即时下单，2，反向下单
    'grid_deep': 4, # 网格深度
    'grid_rate': 1, #网格每次加仓间隔率
    'g_add_type': 1,  #网格加仓类型：1为固定加仓，2为倍数加仓
    'grid_mult': 1, #倍数马丁加仓率
    }, #网格交易
    'combination':{
    'combin_names': ['trend_track','upswing_trend','pullback_trading','manual'], #策略组合名称
    'combin_mode': 1, #策略组合方式：1，间隔亏损次数更换，2，间隔指定次数更换
    'combin_params': 3, #策略组合方式的附加参数，对应方式1，形式为整数如1，对应方式2，形式为数组，如[2,8,10,12]注意次数组长度要小于策略数组长度
    }, #组合策略
    
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
    'prbull': 4, #多头止盈率
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
    'breakeven': 5, #保本退出，即在指定亏损次数后根据亏损额自动生成止盈位置
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
    'breakeven': 5, #保本退出，即在指定亏损次数后根据亏损额自动生成止盈位置
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
    'strategy':'pullback_trading', #策略名称
    'symbol': 'DAR/USDT:USDT', #品种名称
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
    'add_pos': 4, #加仓，0为不加仓，大于0为加仓倍数，初始为1U
    'add_rate': 0.2, #加仓线，为止损线正向叠加率
    'add_loss': 0, #亏损次数以上叠加
    'matin': 0, #开启叠加马丁
    'm_type': 1, #叠加马丁类型 1为总计数叠加，2为多空分别计算叠加
    'm_loss': 6, #叠加马丁最高亏算次数
    'm_muti': 1.5, #叠加马丁下单倍数
    'm_lever': 3, #叠加马丁每层下单次数
    'breakeven': 5, #保本退出，即在指定亏损次数后根据亏损额自动生成止盈位置
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
    'strategy':'pullback_trading', #策略名称
    'symbol': 'FXS/USDT:USDT', #品种名称
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
    'add_pos': 4, #加仓，0为不加仓，大于0为加仓倍数，初始为1U
    'add_rate': 0.2, #加仓线，为止损线正向叠加率
    'add_loss': 0, #亏损次数以上叠加
    'matin': 0, #开启叠加马丁
    'm_type': 1, #叠加马丁类型 1为总计数叠加，2为多空分别计算叠加
    'm_loss': 6, #叠加马丁最高亏算次数
    'm_muti': 1.5, #叠加马丁下单倍数
    'm_lever': 3, #叠加马丁每层下单次数
    'breakeven': 5, #保本退出，即在指定亏损次数后根据亏损额自动生成止盈位置
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
    'strategy':'pullback_trading', #策略名称
    'symbol': 'PYTH/USDT:USDT', #品种名称
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
    'add_pos': 4, #加仓，0为不加仓，大于0为加仓倍数，初始为1U
    'add_rate': 0.2, #加仓线，为止损线正向叠加率
    'add_loss': 0, #亏损次数以上叠加
    'matin': 0, #开启叠加马丁
    'm_type': 1, #叠加马丁类型 1为总计数叠加，2为多空分别计算叠加
    'm_loss': 6, #叠加马丁最高亏算次数
    'm_muti': 1.5, #叠加马丁下单倍数
    'm_lever': 3, #叠加马丁每层下单次数
    'breakeven': 5, #保本退出，即在指定亏损次数后根据亏损额自动生成止盈位置
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

    'start': 1, #0为关闭，1为开启
    'strategy':'pullback_trading', #策略名称
    'symbol': 'COTI/USDT:USDT', #品种名称
    'period':'3m', #周期
    'leverage': 20, #杠杆
    'multiple': 1, #下单倍数，初始1U
    'direct': -1, #指定交易方向，0为多空，1为多，-1为空
    'pr_type': 1, #止盈类型：1为亏损加设定止盈率，2为单止盈不叠加亏损，3为移动止盈
    'prbull': 10, #多头止盈率
    'prbear': 10, #空头止盈率
    'activationRate': 3, #移动止盈触发盈利率
    'callbackRate': 1, #移动止盈触发止盈回撤率
    'st_type': 1, #止损类型，0为不止损，1，为策略止损，3为固定止损
    'st_times': 99, #最大止损次数
    'st_rate': 1.5, #固定止损率
    'add_pos': 0, #加仓，0为不加仓，大于0为加仓倍数，初始为1U
    'add_rate': 0.2, #加仓线，为止损线正向叠加率
    'add_loss': 0, #亏损次数以上叠加
    'matin': 1, #开启叠加马丁
    'm_type': 1, #叠加马丁类型 1为总计数叠加，2为多空分别计算叠加
    'm_loss': 10, #叠加马丁最高亏算次数
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
    'strategy':'combination', #策略名称
    'symbol': 'ALICE/USDT:USDT', #品种名称
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
    'add_pos': 4, #加仓，0为不加仓，大于0为加仓倍数，初始为1U
    'add_rate': 0.2, #加仓线，为止损线正向叠加率
    'add_loss': 0, #亏损次数以上叠加
    'matin': 0, #开启叠加马丁
    'm_type': 1, #叠加马丁类型 1为总计数叠加，2为多空分别计算叠加
    'm_loss': 6, #叠加马丁最高亏算次数
    'm_muti': 1.5, #叠加马丁下单倍数
    'm_lever': 3, #叠加马丁每层下单次数
    'breakeven': 5, #保本退出，即在指定亏损次数后根据亏损额自动生成止盈位置
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
    'combination':{
    'combin_names': ['trend_track','upswing_trend','pullback_trading','manual'], #策略组合名称
    'combin_mode': 1, #策略组合方式：1，间隔亏损次数更换，2，间隔指定次数更换
    'combin_params': 3, #策略组合方式的附加参数，对应方式1，形式为整数如1，对应方式2，形式为数组，如[2,8,10,12]注意次数组长度要小于策略数组长度
    }, #组合策略
    
    },
  
'robot10': {

    'start': 0, #0为关闭，1为开启
    'strategy':'pullback_trading', #策略名称
    'symbol': '1000PEPE/USDT:USDT', #品种名称
    'period':'3m', #周期
    'leverage': 20, #杠杆
    'multiple': 4, #下单倍数，初始1U
    'direct': 1, #指定交易方向，0为多空，1为多，-1为空
    'pr_type': 1, #止盈类型：1为亏损加设定止盈率，2为单止盈不叠加亏损，3为移动止盈
    'prbull': 6, #多头止盈率
    'prbear': 6, #空头止盈率
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
    'breakeven': 4, #保本退出，即在指定亏损次数后根据亏损额自动生成止盈位置
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
    
    'start': 1, #0为关闭，1为开启
    'init': 1, #初始化策略，在关闭时起作用
    'strategy':'trend_track', #策略名称
    'symbol': '1000PEPE/USDT:USDT', #品种名称
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
    'li_profit_times': 99, #全局最大盈利次数
    'li_profit_gaol': 100000000, #全局最大盈利额
    'add_pos': 4, #加仓，0为不加仓，大于0为加仓倍数，初始为1U
    'add_rate': 0.2, #加仓线，为止损线正向叠加率
    'add_loss': 0, #亏损次数以上叠加
    'matin': 0, #开启叠加马丁
    'm_type': 1, #叠加马丁类型 1为总计数叠加，2为多空分别计算叠加
    'm_loss': 6, #叠加马丁最高亏算次数
    'm_muti': 1.5, #叠加马丁下单倍数
    'm_lever': 3, #叠加马丁每层下单次数
    'breakeven': 5, #保本退出，即在指定亏损次数后根据亏损额自动生成止盈位置
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
    'combination':{
    'combin_names': ['trend_track','upswing_trend','pullback_trading','manual'], #策略组合名称
    'combin_mode': 1, #策略组合方式：1，间隔亏损次数更换，2，间隔指定次数更换
    'combin_params': 3, #策略组合方式的附加参数，对应方式1，形式为整数如1，对应方式2，形式为数组，如[2,8,10,12]注意次数组长度要小于策略数组长度
    }, #组合策略
    },
        
}
