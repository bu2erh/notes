**安装软件

Homebrew https://brew.sh/

#国内源

#安装 

/bin/zsh -c "$(curl -fsSL https://gitee.com/cunkai/HomebrewCN/raw/master/Homebrew.sh)"

卸载
/bin/zsh -c "$(curl -fsSL https://gitee.com/cunkai/HomebrewCN/raw/master/HomebrewUninstall.sh)"
软件
 谷歌/edge
brew install --cask google-chrome  
brew install --cask microsoft-edge
nvm    
brew install nvm   
nvm install 16
npm install nrm -g
pnpm
brew install pnpm
vscode
brew install --cask visual-studio-code
微信开发者工具
brew install --cask wechatwebdevtools
postman
brew install --cask postman
MacZip
brew install --cask maczip

brew install --cask wechat
brew install --cask qq
brew install --cask youdaodict   网易有道词典
brew install --cask mailmaster   网易邮箱大师
brew install --cask neteasemusic 网易云音乐
安装问题
nvm
mkdir ~/.nvm

vi ~/.zshrc

export NVM_DIR="$HOME/.nvm"
[ -s "/usr/local/opt/nvm/nvm.sh" ] && . "/usr/local/opt/nvm/nvm.sh"
[ -s "/usr/local/opt/nvm/etc/bash_completion.d/nvm" ] && . "/usr/local/opt/nvm/etc/bash_completion.d/nvm"

:wq

source ~/.zshrc
