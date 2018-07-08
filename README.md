# Mac Auto Setup By nagaminenot

## How to Use
```bash
# install homebrew
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
# install ansible
brew install ansible
# run ansible-playbook
ansible-playbook -i localhost site.yml -vv --ask-become-pass
# Path to config.fish
source ~/.config/fish/config.fish
# get omf & bobthefish
curl -L http://get.oh-my.fish | fish ; omf install bobthefish
```

## Reffer
<https://techte.co/2018/01/22/ansible-mac/#site-yml>