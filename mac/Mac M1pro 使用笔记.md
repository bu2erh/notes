# 安装Homebrew 
https://brew.sh/
## 国内源 
https://gitee.com/cunkai/HomebrewCN
- 安装 
```
/bin/zsh -c "$(curl -fsSL https://gitee.com/cunkai/HomebrewCN/raw/master/Homebrew.sh)"
```
- 卸载
```
/bin/zsh -c "$(curl -fsSL https://gitee.com/cunkai/HomebrewCN/raw/master/HomebrewUninstall.sh)"
```
苹果 M1 Pro 电脑上使用 Homebrew 的过程中，可以选择使用国内的源，比如清华源或中科大源。以下是切换过程：

1. 首先打开终端，进入 Homebrew 目录，输入以下命令：

```
cd "$(brew --repo)"
```

2. 接着添加清华源，输入以下命令：

```
git remote set-url origin https://mirrors.tuna.tsinghua.edu.cn/git/homebrew/brew.git
```

3. 或者添加中科大源，输入以下命令：

```
git remote set-url origin https://mirrors.ustc.edu.cn/brew.git
```

4. 然后更新 Homebrew，输入以下命令：

```
brew update
```

5. 最后可以测试一下，输入以下命令，查看是否已经切换成功：

```
brew doctor
```

如果显示的信息中有清华或中科大的字样，就说明已经切换成功了。
## 软件
```
brew install --cask google-chrome  
```
```
brew install --cask microsoft-edge
```
```
brew install nvm   
```
```
nvm install 16
```
brew install nrm
```
brew install pnpm
```
```
brew install --cask visual-studio-code
```
```
brew install --cask wechatwebdevtools
```
```
brew install --cask postman
```
```
brew install --cask maczip
```
```
brew install --cask snipaste
```
```
brew install --cask cheatsheet
```
```
brew install --cask eudic
```
```
brew install --cask nosleep
```
```
brew install --cask sunloginclient
```
```
brew install --cask wechat
```
```
brew install --cask qq
```
```
brew install --cask youdaodict
```
```
brew install --cask mailmaster
```
```
brew install --cask neteasemusic
```
## 安装问题
- nvm
```
mkdir ~/.nvm
```
```
vi ~/.zshrc
```
```
export NVM_DIR="$HOME/.nvm"
  [ -s "/opt/homebrew/opt/nvm/nvm.sh" ] && \. "/opt/homebrew/opt/nvm/nvm.sh"  # This loads nvm
  [ -s "/opt/homebrew/opt/nvm/etc/bash_completion.d/nvm" ] && \. "/opt/homebrew/opt/nvm/etc/bash_completion.d/nvm"  # This loads nvm bash_completion
```
```
:wq
```
```
source ~/.zshrc
```
