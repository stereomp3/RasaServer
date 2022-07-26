# Rasa

Rasa is a Python-based bot framework. It works with the **Python version >= 3.6, < 3.9**

[rasa official website](https://rasa.com/docs/rasa/)、[rasa github](https://github.com/RasaHQ/rasa)、[Install instructional video](https://www.youtube.com/watch?v=4ewIABo0OkU)、[Training Data and Rules](https://www.youtube.com/watch?v=8gvGh6H2NO0)



## installation steps (use anaconda)

* cd to project folder

* `conda create --name installingRasa python==3.7.6`

* `conda activate installingRasa` 

* `conda install ujson` (help us with the more dependencies that we need to install)

* `conda install tensorflow`

* `pip install rasa`

* `rasa init` (initialization project ,  `. `,  `y`,  `y`)



[rasa command line](https://rasa.com/docs/rasa/command-line-interface/)

start server: `rasa run`



## active server 

```sh
conda activate installingRasa
rasa run
```





## anaconda

* 建立虛擬環境: `conda create -n 指定虛擬環境名稱 python=指定版本號碼`(不指定會妝最新的)
* 查看虛擬環境: `conda env list`
* 切換虛擬環境: `activate 指定虛擬環境`
* 退出虛擬環境: `deactivate`



* 使用: pip install maplotlib 可以裝各種套件
* 使用python 檔名.py開啟檔案
* 切換到D槽: d:



## else

costom connectors: https://rasa.com/docs/rasa/connectors/custom-connectors/

```sh
await window.fetch('./webhooks/myio/webhook', {
        body: {
          "sender": "test_user",  
          "message": "Hi there!",
          "metadata": {}
        },
        method: 'POST',
        headers: {
        'Content-Type': 'application/json'
        }
    })
```

