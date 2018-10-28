# macOS 装机

## macOS 软件

### 终端

iterm2 最牛macOS终端

```
brew cask install iterm2
```

### 科学上网

shadowsocks 客户端

```
brew cask install shadowsocksx-ng
```

### 浏览器

最爱浏览器chrome

```
brew cask install google-chrome
```

### 写作

typora 所写即所见，界面优美，目前免费。

```
brew cask install typora
```

### 影音

vlc 视频解码&播放

```
brew cask install vlc
```

### 云盘同步

- 坚果云
> 国内一级棒的云同步软件

```
brew cask install nutstore
```

### 办公软件

苹果官方三件套
> 使用App Store安装

- Pages
- Keynote
- Numbers

多人协作文档

- 石墨文档

```
brew cask install shimo
```

邮箱

- 网易邮箱大师

```
brew cask install mailmaster
```

### IM

- telegram

```
brew cask install telegram
```

- 微信

```
brew cask install wechat
```

- 钉钉

```
brew cask install dingtalk
```

- slack

```
brew cask install slack
```

### 效率工具

- Trello
> 协作看板工具
> 使用App Store安装

- workflowy
> 无限层级Outline，最爱

```
brew cask install workflowy
```

- 笔记工具，有道笔记

```
brew cask install youdaonote
```

### 开发工具

- WireShark 抓包工具

```
brew cask install wireshark
```

- VSCode 代码编辑工具

```
brew cask install visual-studio-code
```

- Docker
> Docker macOS版

```
brew cask install docker
```

- 数据库工具 dbeaver

```
brew cask install dbeaver-community
```

### 系统工具

- 程序卸载工具 appcleaner

```
brew cask install appcleaner
```

- 压缩解压 keka

```
brew cask install keka
```

- 窗口控制程序 spectacle

```
brew cask install spectacle
```

- 壁纸 Wallcat
> 使用App Store安装

每天自动替换不同的美丽背景

- 密码管理工具 enpass

```
brew cask install enpass
```

- 远程办公 teamviewer

```
brew cask install teamviewer
```

- 命令提示 cheatsheet

```
brew cask install cheatsheet
```

### 命令行工具

- oh my zsh
TODO

- cmake

```
brew install cmake
```

- cscope

```
brew install cscope
```

- ctags 

```
brew install ctags
```

- the silver searcher

```
brew install the_silver_searcher
```

- vim
TODO

```
brew install vim
```

- go

```
brew install go
```

## 修改默认设置

1. 把 F1-F12 改成标准功能键
2. 设置 Trackpad 轻点来点按
3. 键盘按键速度调到最快
4. Dock位置改在左边

## 常用命令

### 重置Launchpad图标位置

defaults write com.apple.dock ResetLaunchPad -bool true; killall Dock

