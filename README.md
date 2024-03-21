# EECE-5642-Data-Virtualization
This is the final project of EECE 5642 in northeastern university, we are trying to virtualize the music features extracted from ai or traditional math method.



点子1 (瓶颈，不知道怎么实现，提取特征很简单，但是然后呢，不知道该干嘛)
主要是针对音乐分类的研究，手工或者神经网络提取特征并将特征可视化，目的是对比我们手工提取出的特征和神经网络提取出的特征，正常情况下人是根据手工提取出的特征来区分歌曲，而人工智能则是根据自己学出来的特征，我们的任务就是把提取出来的特征行可视化的呈现。（暂定不太可行，没有找到我理想中的资料）没有办法提取出我想要的音频特征

特征值可视化：
https://zhuanlan.zhihu.com/p/144685755

音频处理的python库：
https://librosa.org/doc/latest/tutorial.html

使用librosa提取歌曲的特征和可视化：
https://blog.csdn.net/ahong286286/article/details/90170749?utm_medium=distribute.pc_relevant.none-task-blog-2~default~baidujs_baidulandingword~default-0-90170749-blog-89677759.235^v43^pc_blog_bottom_relevance_base7&spm=1001.2101.3001.4242.1&utm_relevant_index=3

音频分析fft效果: release.rar

用FFT实现音频分析 讲的比较清楚:
https://zhuanlan.zhihu.com/p/363561594?utm_id=0

音乐信号音符/乐谱提取: https://blog.csdn.net/qq_21210467/article/details/80273411?utm_medium=distribute.pc_relevant.none-task-blog-2~default~baidujs_baidulandingword~default-4-80273411-blog-110629718.235^v43^pc_blog_bottom_relevance_base9&spm=1001.2101.3001.4242.3&utm_relevant_index=7




点子2 (刚刚想到的，我们可以直接用别人的神经网络提取信息然后可视化，比我们传统的fft效果要好，主要是能分离出来具体的音轨，比如吉他，键盘，架子鼓等等，这些东西传统的fft是做不到的，我们可以根据每一个音轨做一个可视化，最后能做成一个类似于瀑布流一样的东西，每一个音轨都有自己的瀑布，然后随着时间一起动)

https://github.com/magenta/mt3

使用谷歌的开源模型MT3直接提取出音频文件，转化为midi文件，最终将midi文件中的音轨可视化，通过midi文件你可以找到比如说一首歌中有多少音，等等，另外可以针对每一个音轨做一个类似于流动的可视化（暂时没有想到怎么做）
但是使用这个点子就需要一些别的工作，因为使用的别人的模型，所以我们的重点是在可视化上，模型已经可以输出相当精确的音轨了







