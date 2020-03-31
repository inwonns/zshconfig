# install zsh and configuration #####

1. install zsh (brew, yum, apt-get)
   brew install zsh
   yum install zsh
   ...
2. install oh-my-zsh 
   curl -L https://github.com/robbyrussell/oh-my-zsh/raw/master/tools/install.sh | sh 

3. add /usr/bin/zsh into /etc/shells

4. as root 
   chsh -s /usr/bin/zsh username

5. copy .zshrc into your home

6. vi .zshrc and modify ZSH path
