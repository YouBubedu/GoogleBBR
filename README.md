#                             Google TCP BBr网络加速脚本
使用方法 

    wget --no-check-certificate https://github.com/YouBubedu/GoogleBBR/raw/master/BBR.sh && sh BBR.sh


安装过程中会提示更换内核,</br>
所以为安全起见，请勿在生产环境下运行，经过测试可用后，再操作。</br>
更换内核选择“是”</br>
等待安装，之后重启服务器即可。

验证是否安装成功 

    执行 lsmod | grep bbr
   
如果结果显示bbr便安装成功

注意：不支持Ovz虚拟技术的机器，不支持Ovz虚拟技术的机器，不支持Ovz虚拟技术的机器！！！

鸣谢@Fancy大佬
