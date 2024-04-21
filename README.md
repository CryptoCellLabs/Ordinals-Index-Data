# Ordinals Index Data (2024/04/21 - height 840178)
# Ordinals Index Data索引文件 (2024/04/21 - 区块高度 840178)

Ordinals Index Data

Ordinals Index Data File Index.redb (Ordinals Index Data Index.redb)

Index.redb updated to block height 840178 of Bitcoin full node (2024/04/21)
Link: https://pan.quark.cn/s/8b0851383fda

Bitcoin Full Node Data(2024/04/21)
https://github.com/CryptoCellLabs/Bitcoin_FullNode_Data 

--------------------------
Ordinals索引数据文件Index.redb（Ordinals Index Data Index.redb）

Index.redb更新到Bitcoin全节点840178区块高度(2024/04/21)

链接：https://pan.quark.cn/s/8b0851383fda

下载后请校验index.redb文件的SHA256，以便核对文件完整性
----------------------------
Bitcoin 全节点数据（更新到2024/04/21）
https://github.com/CryptoCellLabs/Bitcoin_FullNode_Data 

Ordinals/Runes铭文教程（含Bitcoin全节点数据/Bitcoin Index数据/ORD Runes Index数据）
https://mirror.xyz/cryptocelllabs.eth/HZKYY-0o23GllhstDHzgiC6De4rzWJ6Dr2y8lDnY3bI

--------------------------

目前BTC全节点完整数据在700G左右了，如果自行同步比较慢的话，可以直接去下面地址的网盘下载 Bitcoin全节点完整数据 – 更新到2024年4月19日 ，包含如下数据：

1、Bitcoin全节点数据（大约690G）

2、Bitcoin全节点Index索引数据（大约70G）

3、Ordinals/Runes Index索引数据（大约200G）

https://github.com/CryptoCellLabs/Bitcoin_FullNode_Data

或者关注Twitter https://twitter.com/CryptoCellLabs

Ordinals Runes Index DB数据大约200G，同样可以在上面的网盘下载

由于Bitcoin全节点数据 + Bitcoin全节点索引Index数据 + Ordinals/Runes Index数据 已经接近1T了，如果需要快速完成这个操作可以直接购买我们存储在机械硬盘中的上述三类数据，拿到快递的硬盘后，你需要准备一个2T的SSD来将这些数据从机械硬盘拷贝过去，因为只有SSD的读写速度才是最佳的。

获得这三类数据的方法：

【第一种】：自行网盘免费下载 ，适合网速很快的同学，下载地址 https://github.com/CryptoCellLabs/Bitcoin_FullNode_Data

下载完成后需要校验所有压缩文件的SHA256数值，确保正确无误后进行解压缩以及其他操作。

【第二种】：直接购买存有上述三类数据的机械硬盘（机械硬盘只是为了数据运输，你拿到数据后还是需要一个2T SSD）

购买链接地址  http://buy.btcfullnode.org


ORD 的使用帮助

1. 下载官方最新的 ORD 版本
https://github.com/ordinals/ord/releases

2. 先查看简单说明
ord.exe -h

这会列出所有相关的参数跟命令

3. 将下载的ord-index-db文件（index.redb）拷贝到需要的目录

4. 开始同步资料库
以下范例：
ord.exe --cookie-file "Ｅ:\bitcoin\block\.cookie"  --data-dir "E:\bitcoin\ord" --index-runes index update

参数说明：
--cookie-file 执行 bitcoin core 时在资料夹里会有 .cookie 档案 指定好他的路径即可

--data-dir 这里是存放 ord 索引资料库 index.redb 档案的位置 请选择有足够空间的位置

-index-runes index update 更新索引的命令

-------------------
HOW TO FIX "os error 10053" when creating ord index?

Info:
error: JSON-RPC error: transport error: Couldn't connect to host: An established connection was aborted by the software in your host machine. (os error 10053)

FIX:

1.Run ord

2.Then crtl+c shutdown ord when the index was just a few hundred blocks away from the problematic block.

3.Run ord again

 
-------------------
Ordinals最新消息（Ordinals News）
Twitter 
https://twitter.com/CryptoCellLabs 


