
 # RUN CONTAINER
 
 コマンド`docker container run -t ubuntu top`を実行
 ```
 Unable to find image 'ubuntu:latest' locally
latest: Pulling from library/ubuntu
32802c0cfa4d: Pull complete 
da1315cffa03: Pull complete 
fa83472a3562: Pull complete 
f85999a86bef: Pull complete 
Digest: sha256:6d0e0c26489e33f5a6f0020edface2727db9489744ecc9b4f50c7fa671f23c49
Status: Downloaded newer image for ubuntu:latest

top - 04:24:20 up  3:05,  0 users,  load average: 0.13, 0.28, 0.24
Tasks:   1 total,   1 running,   0 sleeping,   0 stopped,   0 zombie
%Cpu(s):  1.7 us,  1.9 sy,  0.0 ni, 96.2 id,  0.2 wa,  0.0 hi,  0.0 si,  0.0 st
KiB Mem :  2046940 total,    89048 free,  1440364 used,   517528 buff/cache
KiB Swap:  1048572 total,   955416 free,    93156 used.   403704 avail Mem 

  PID USER      PR  NI    VIRT    RES    SHR S  %CPU %MEM     TIME+ COMMAND                                                                                                            
    1 root      20   0   36588   3160   2732 R   0.0  0.2   0:00.32 top                                                                                                               
```

`docker container ls`は実行中のコンテナを表示
`docker container exec -it [ubuntu CONTAINER ID] bash`でubuntuのbashを起動
 
