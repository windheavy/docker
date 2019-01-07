#仮想マシンとコンテナの違い

![image](/images/cont_vm.png)

- VMはハードウェア上にハイパーバイザで動く、仮想化されて独立したmachine(コンピュータ)のこと
- VMはCPUやメモリなどの物理資源を分割して、仮想マシンに提供している
- 各VM上異なるOSがインストール可能

- コンテナはOS上、linuxをベースにdockerで分離して個々の独立したプロセス(or group of process)のこと

