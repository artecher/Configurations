# must install myzsh first, otherwise ~ is not working
# Configurations
## clone {this repo}
 - ln -sf ~/Configurations/karabiner ~/.config/karabiner
 - ln -sf ~/Configurations/.ssh/config ~/.ssh/config
 - ln -sf ~/Configurations/.gitconfig ~/.gitconfig
 - ln -sf ~/Configurations/.gitignore_global ~/.gitignore_global
 - ln -sf ~/Configurations/.zshrc ~/.zshrc
# Change the default KeyRepeat and InitialKeyRepeat
- defaults write -g InitialKeyRepeat -int 15 # normal minimum is 15 (225 ms)
- defaults write -g KeyRepeat -int 1.5 # normal minimum is 2 (30 ms)
