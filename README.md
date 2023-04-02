# action_recognition
一个简单的行为识别小demo  for beginner

用的ucf-101数据集，里面有101种行为，足够了。数据集链接：https://www.crcv.ucf.edu/data/UCF101.php（有点大，准备好空闲时间下载）
用的ConvLSTM实现，这部分花了我很久时间，建议大家把原理弄清楚再写代码
我是用的人家的预训练模型 然后迁移学习，由于是用来学习的，所以只跑了不到100个epoch，能有90%+的accuracy



