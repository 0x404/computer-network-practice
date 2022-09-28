# 作业演示

计算机网络多线程CGI服务器作业演示，**Python版本>=3.9**

## 使用方法

### 安装cgi-server
本仓库通过自己实现的服务器框架[`cgi-server`](https://github.com/0x404/cgi-server)实现，在运行前需要安装该服务器框架。
#### 从PyPI上安装
运行如下命令
```shell
pip3 install cgi-server
```
#### 从源码安装
运行如下命令
```shell
git clone git@github.com:0x404/cgi-server.git

cd cgi-server

python3 setup.py install
```

### 运行
服务启动入口为`main.py`，运行如下命令

```shell
python3 main.py --host 127.0.0.1 --port 8888
```

此时你可以在`http://127.0.0.1:8888`看到对应的网页界面

更多使用说明可以通过如下命令查看帮助说明

```shell
python3 main.py -h
```
