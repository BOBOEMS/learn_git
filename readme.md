#
测试使用
设置代理1： git config --global http.proxy http://127.0.0.1:12334
设置代理2： git config --global https.proxy http://127.0.0.1:12334     
查看代理： git config --global --get-regexp proxy 

清楚代理1： git config --global --unset http.proxy
清楚代理2： git config --global --unset https.proxy