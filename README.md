# DB-GPT
A Open Database-GPT Experiment

![GitHub Repo stars](https://img.shields.io/github/stars/csunny/db-gpt?style=social)


DB-GPT is an experimental open-source application that builds upon the fastchat model and uses vicuna as its base model. Additionally, it looks like this application incorporates langchain and llama-index embedding knowledge to improve Database-QA capabilities. 

Overall, it appears to be a sophisticated and innovative tool for working with databases. If you have any specific questions about how to use or implement DB-GPT in your work, please let me know and I'll do my best to assist you.

Run on an RTX 4090 GPU (The origin mov not sped up!, [YouTube地址](https://www.youtube.com/watch?v=1PWI6F89LPo))
- 运行演示
![](https://github.com/csunny/DB-GPT/blob/dev/asserts/演示.gif)

- SQL生成示例

<img src="https://github.com/csunny/DB-GPT/blob/dev/asserts/sql_generate.png" width="600" margin-left="auto" margin-right="auto" >
<hr/>
- 数据库QA示例 

<img src="https://github.com/csunny/DB-GPT/blob/dev/asserts/DB_QA.png" margin-left="auto" margin-right="auto" width="600">

# Install
1. Run model server
```
cd pilot/server
python vicuna_server.py
```

2. Run gradio webui
```
python webserver.py 
```

# Featurs
- SQL-Generate
- Database-QA Based Knowledge 
- SQL-diagnosis