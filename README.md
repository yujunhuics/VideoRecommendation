# VideoRecommendation
 2021 DIGIX 全球校园AI算法精英大赛-基于多目标优化的视频推荐-baseline

## 赛题介绍
推荐系统大多都是基于隐式反馈来做推荐，比如用户的点击、观看时长、评论、分享等，且不同隐式反馈表达了用户不同的喜好程度。如果仅仅以单目标对推荐结果进行衡量，会存在衡量不全面的问题。如视频场景，假设某个用户打开一个视频看了开头觉得不喜欢立马关掉，如果以点击为目标则体现的是用户感兴趣，但实际情况是用户对这个视频不感兴趣。从这个例子可以看出，在视频推荐中如果仅仅以点击为目标，可能忽视了用户更深层次的隐式反馈。因此，视频推荐除了关注用户点击，还需关注用户观看时长、分享等目标，期望通过多目标能更深入地挖掘用户兴趣，做更精准的推荐。

[赛题链接](https://developer.huawei.com/consumer/cn/activity/devStarAI/algo/competition.html#/preliminary/info/006/introduction)

## 使用方法
process.py:生成tfrecord数据。

train_model.py:训练模型

3、predict.py:预测结果