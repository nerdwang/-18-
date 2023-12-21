# 商务智能第18组大作业 Navigating Truth: Leveraging NLP to Detect Fake News
原始数据、clean data、all-mpnet-base-v2模型保存在这里。

预训练的glove embedding可以从https://www.kaggle.com/datasets/bertcarremans/glovetwitter27b100dtxt 下载。

text-embedding-ada-002的调用，在https://platform.openai.com/docs/overview 注册一个openai账号，然后充值一定的api额度，创建一个自己的api key，在openai-gpt3.ipynb里os.environ["OPENAI_API_KEY"] = "这里填入自己的openai api"这一行替换成自己的openai api key即可调用。
