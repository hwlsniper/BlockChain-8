# BlockChain
区块链项目
目前是基础版本，共识机制还未完成
下一个版本打算做成cloud

#一致性
区块链系统应该是分布式的,所以我们要保证所有节点有同样的链。
一致性是为了解决冲突。
冲突？（是指不同的节点拥有不同的链）
解决:规定最长的,有效的链才是最终的链。

#注册节点
在实现算法一致性之前,我们需要找到一种方式让一个节点知道他相邻的节点。每个节点
都需要保存一份包含网络中其它节点的记录
