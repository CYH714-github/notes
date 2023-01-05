# Git报错

`Failed to connect to github.com port 443:connection timed out`

打开Git Bash，输入`git config --global http.proxy http://127.0.0.1:1080`（进行代理）

再输入`git config --global --unset http.proxy`（取消代理）即可