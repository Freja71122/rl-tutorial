# Stable Baselines3 基础手册

Stable Baselines3（下文简称 sb3）是一个非常受欢迎的 RL 工具包，**用户只需要定义清楚环境和算法，sb3 就能十分优雅的完成训练和评估。**

这一篇会介绍 Stable Baselines3 的基础：
- 如何进行 RL 训练和测试？
- 如何可视化训练效果？
- 如何创建自定义环境？

**首先回顾一下，RL 中最核心的两个组件：智能体 Agent 和环境 Environment：**
- 智能体是 sb3 中提供的模型
- sb3 使用 Gym 作为交互环境，包括 Gym 中提供的、或者用户自定义的环境（需要继承 gym.Env)


## 参考
https://github.com/araffin/rl-tutorial-jnrr19