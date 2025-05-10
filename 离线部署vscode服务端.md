# 离线部署vscode服务端

```bash
# 在vscode 菜单help/about中查看commit id
# 下载vscode server
https://update.code.visualstudio.com/commit:commit_id/server-linux-x64/stable

# 拷贝到目标机器，然后执行如下命令安装
mkdir -p ~/.vscode-server/bin/commit_id
tar xf vscode-server-linux-x64.tar.gz   --strip-components=1 -C  ~/.vscode-server/bin/commit_id
```