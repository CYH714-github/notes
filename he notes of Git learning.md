# The notes of Git learning

Maybe I should use English to write some notes which will improve my English ability.Though my grammar and spelling are like trash, I believe improvements will appear over time. This time I integrate two passages into an English version.

VSCode offers a perfect git sync method that allows you to push/sync your files. Just choose your folder and it will help you create a github repository automatically. Then you can use it to sync.

![VSCode git interface](https://s2.loli.net/2022/08/10/fkM2WmZuGKOPXRU.png)

## Problem

I used to meet a strange problem, the error is `Failed to connect to github.com port 443:connection timed out` when I use a proxy service.

The solution is to open Git Bash and enter `git config --global http.proxy 127.0.0.1:7890` (to use the proxy, 7890 is my port, you need to change it to your proxy port).