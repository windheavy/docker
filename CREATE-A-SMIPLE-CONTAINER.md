# まずは一番単純なosしか入ってないコンテナを立ててみる

ubuntuのコンテナを立てて、top コマンドを実行
`docker container run -t ubuntu top`

実行結果
```
$ docker container run -t ubuntu top
Unable to find image 'ubuntu:latest' locally 
latest: Pulling from library/ubuntu
38e2e6cd5626: Pull complete 
705054bc3f5b: Pull complete 
c7051e069564: Pull complete 
7308e914506c: Pull complete 
Digest: sha256:945039273a7b927869a07b375dc3148de16865de44dec8398672977e050a072e
Status: Downloaded newer image for ubuntu:latest
```
top
```
top - 02:09:46 up 1 day,  7:50,  0 users,  load average: 0.21, 0.13, 0.04
Tasks:   1 total,   1 running,   0 sleeping,   0 stopped,   0 zombie
%Cpu(s):  0.0 us,  0.2 sy,  0.0 ni, 99.8 id,  0.0 wa,  0.0 hi,  0.0 si,  0.0 st
KiB Mem :  2046940 total,  1184612 free,   203080 used,   659248 buff/cache
KiB Swap:  1048572 total,   997816 free,    50756 used.  1689116 avail Mem 

  PID USER      PR  NI    VIRT    RES    SHR S  %CPU %MEM     TIME+ COMMAND                                                                                                                                                                 
    1 root      20   0   36588   3240   2816 R   0.3  0.2   0:00.09 top    
```
