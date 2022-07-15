
<div align="center">
    <img src="https://github.com/Yanizi/bot/blob/main/img/536083.png?raw=true">
</div>


## redis
- 端口：9123 
- 6379是redis默认端口，尽量别用，一定要设置密码
```python
'redis://user:密码@IP:端口/0'
```


## 配置文件 tgbot/coonfig.py
- 设置机器人的TOKEN
- 设置redis地址




## 机器人命令
- start - 开始
- help - 帮助
- key - 充值卡密


## 测试卡密
yaniz





## 虚拟环境

### 安装

> 安装conda

```
wget -c https://repo.continuum.io/miniconda/Miniconda3-latest-Linux-x86_64.sh
#给执行权限
chmod 777 Miniconda3-latest-Linux-x86_64.sh 
#运行 安装, 一直回车即可
bash Miniconda3-latest-Linux-x86_64.sh 
```



### 查看所有环境

```
conda info -e
```



### 创建环境

> python=3自动安装最新python
>
>  --name 后面指定虚拟环境的名字

```
conda create --name test1 python=3
```



### 切换环境
```python
source activate yaniz # 切换到名为yaniz的虚拟环境
```



### 删除环境

> yaniz替换成你要删除的 虚拟环境

```
conda remove -n yaniz --all
```



### 退出环境

```
conda deactivate
```





## 安装所需要的包

> 项目中有requirements.txt

```
pip install -r requirements.txt
```

