# KaiWu-Seminar

Pre-Workshop on Seminar of Kaiwu Competition

## 1.欢迎!!!

欢迎同学们积极参与开悟，在强化学习的深坑边上开始作死试探(￣▽￣)~*

考虑到各位最近期末周正忙，我们将在6月30号举办一场研讨会，各位请做好准备，向你们的peers分享你们最近的学习心得，例如强化学习的原理，调参经验和git命令等。研讨会后我们会决定今年参赛的大名单，所以请认真准备。

## 2. A Little Test

在分享会前，我们需要通过一些测试了解大家的水平，以及在通过测试的历练后获得对强化学习的初步认知。

### 2.1 测试题目

本次测试题目环境为gym上的LunarLander-v2，使用Pytorch框架，不指定版本

1.必须实现的的：DQN算法和PPO算法,并用TensorBoard/matplotlib绘制性能曲线

3.可选的：DQN变体算法的实现（例如D3QN），PPO的算法的改进（例如 lstm+PPO/GRU+PPO/TransFormer+PPO/Dual PPO)，测试torch.compile带来的性能提升（pytorch2.0后拥有的新函数，在首次编译后可提升训练速度）

3.可选阅读材料：腾讯在AAAI上发布的有关强化学习的论文，去年复赛的代码和Games core

### 2.2 提交方式

请上传到自己github仓库，并在群里贴上自己的仓库链接。仓库中需包含  'performance.png'（性能曲线），'record.gif'（游戏效果展示） 和'readme.md' （一份markdown格式的说明文档）,且保留权重文件和requirements.txt/config,yml(pip或conda环境导出)，确保结果是可复现的。我们将使用MOSS等工具进行代码查重。会查重！会查重！会查重！截止日期为6月29日，超过时间则分数衰减(我们会查看commit记录)。

### 2.3 参考资料

[lazavgeridis/LunarLander-v2: Implementation of reinforcement learning algorithms for the OpenAI Gym environment LunarLander-v2 (github.com)](https://github.com/lazavgeridis/LunarLander-v2)

[Reinforcement Learning (DQN) Tutorial — PyTorch Tutorials 2.3.0+cu121 documentation](https://pytorch.org/tutorials/intermediate/reinforcement_q_learning.html)

[Welcome to Spinning Up in Deep RL! — Spinning Up documentation (openai.com)](https://spinningup.openai.com/en/latest/)

[ZhiyeTang/Kaiwu-Paper-List: 深圳大学X腾讯开悟教学项目：论文阅读清单 (github.com)](https://github.com/ZhiyeTang/Kaiwu-Paper-List)

[boyu-ai/Hands-on-RL: https://hrl.boyuai.com/ (github.com)](https://github.com/boyu-ai/Hands-on-RL)

[MathFoundationRL/Book-Mathematical-Foundation-of-Reinforcement-Learning: This is the homepage of a new book entitled &#34;Mathematical Foundations of Reinforcement Learning.&#34; (github.com)](https://github.com/MathFoundationRL/Book-Mathematical-Foundation-of-Reinforcement-Learning)

（其中最后2个链接分别对应[西湖大学](https://www.bilibili.com/video/BV1sd4y167NS/?vd_source=36094f29bf65fe88d0802302e377b8a2)和[上海交通大学](https://www.boyuai.com/elites/course/xVqhU42F5IDky94x)的公开课程）
