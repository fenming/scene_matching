# scene_matching 存在问题
1.传统的景象匹配算法主要分为三种：基于灰度、基于特征 和解释性
传统统景象匹配任务具有如下难点：
  1.匹配精度受限：由于光照、距离、视角等环境因素发生变化，
  2.适配区制备低效：由于飞行场景复杂多变，有很多特征不明显或者重复模式过多的地区并不适合进行景象匹配，适配区则是那些信息丰富且稳定的地区，因此在无人机挂载景象匹配导航系统之前，通常都需要提前制备适配区
  3.实时性差：景象匹配算法涉及的计算通常比较复杂，而机载处理器计算能力有限，用于无人飞行器定位的景象匹配算法必须采用尽可能简单的方法，才能满足实时性要求。同时必须保证景象匹配效果足够精确，才能得到高精度的定位结果。
