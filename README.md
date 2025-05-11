# swap.sh
Linux VPS一键添加/删除Swap虚拟内存
脚本来自 Moerats 大佬！

说明：很多人的VPS服务器由于内存太小，会导致很多进程被杀掉，这时候就需要我们添加Swap虚拟内存了，这里就整了个一键脚本方便懒人使用。

注意：此脚本不支持OpenVZ架构的VPS，安装会自动退出。

一键命令：

```
wget https://raw.githubusercontent.com/NodeSuper/swap.sh/main/swap.sh && bash swap.sh
```

然后根据选项进行操作，记得添加swap的时候填写纯数字，默认单位为M。
