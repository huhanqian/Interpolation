# Interpolation
//data_a为起始值输入，data_b为终点值输入
//datain_vld为输入数据检测脉冲，只有在此脉冲内检测到的data_a和data_b才会在相应状态被插值输出，
//除非此脉冲内检测到的输入数据被插值输出完成且下一datain_vld脉冲来临，否则新的输入数据无效
//interpolation_out为数据输出
//index为输出数据计数(1为起始值)
//sign_indicate为输出数据符号位
//out_vld为输出有效，out_last为输出的最后一位数据(即终点值)
