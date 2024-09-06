# cobMamba
try to combine cobformer and mamba

跑之前记得先设置metis环境变量
export METIS_DLL=/usr/local/lib/libmetis.so

get_data.py对data_utils的引用在跑main.py的时候改成Data.data_utils，而在跑cal_partition的时候改成data_utils(就是把前面的Data.删了)
