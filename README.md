# chatbot
覆盖银行10个业务场景，分别是查年费，查利率，查交易限额，查明细，查积分，查开户行，查余额，修改密码，信用卡还款方式。意图数量共126个，slot共13个，action共22个。将训练数据以8：2分成训练集和测试集。训练集9735条数据，测试集2386，意图识别准确率为99.2%，实体识别准确率是98.5%，具体请见results文件夹的内容。

实现了同场景下不同分支的跳转，跨场景对话，以及用户简短语句的回答。

![dialogue_1.png](https://s2.loli.net/2022/03/13/PNugqQizdGBH8Ey.png)

![dialogue_2.png](https://s2.loli.net/2022/03/13/T7YGWelnCajqBzI.png)

![dialogue_3.png](https://s2.loli.net/2022/03/13/aCXpZ5Mkcb1qeRr.png)

场景分支图如下：


![Scenes_branch.png](https://s2.loli.net/2022/03/13/9qejYNol6h2wzyL.png)
