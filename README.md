# BlockchainFinalProject

## How to run
1. 启动节点   
   `bash nodes/127.0.0.1/start_all.sh`
   
2. 部署[Python SDK](https://github.com/FISCO-BCOS/python-sdk)
   
3. 将本仓库中的python-sdk文件夹与部署时下载的python-sdk文件夹合并

4. 编译并部署合约，创建表格  
   `python init.py`
   
5. 将main.py中的`to_address`赋值为上一步部署的智能合约的地址（可在控制台查看输出，也可在python-sdk/bin/contract.ini中得到）

6. `python main.py`
