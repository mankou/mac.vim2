# mac.vim2
 * mac上的vim配置
 * 创建于20171101
 * 注 原来我在mac上也配置过vim 但不怎么好用,所以就一直没用起来 现在又重新弄一版 为了区分与原来的那版,所以该版叫mac.vim2, 原来的那一版 mac.vim仍然保留在github上

# 检出步骤

 ```
 # 检出文件
 # 检出YouCompleteMe 时比较慢,请耐心等待
 git clone --recursive git@github.com:mankou/mac.vim2.git ~/.vim
 ln -s ~/.vimrc ~/.vim/.vimrc
 
 # 安装插件
 打开vi 执行 :PluginInstall 命令

# 编译 YouCompleteMe 插件
cd bundle/YouCompleteMe
./install.sh

 ```
