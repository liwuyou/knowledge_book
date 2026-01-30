## git配置
```
查看配置
git config --list

用户配置
git config --global user.name "wuyou"
git config --global user.email "3125172535@qq.com"

清除用户配置
git config --global --unset user.name
git config --global --unset user.email
git config --global --unset user.name user.email


VScode远程仓库配置
在github新建仓库，点击Vscode的初始化仓库，选择远程仓库配置，仓库地址，仓库名随意，一般origin

代理配置
git config --global http.proxy 127.0.0.1:7897
git config --global https.proxy 127.0.0.1:7897

代理清除
# 清除全局代理（最常用）
git config --global --unset http.proxy
git config --global --unset https.proxy

# 清除当前仓库的代理
cd /path/to/your/repo
git config --local --unset http.proxy
git config --local --unset https.proxy

```