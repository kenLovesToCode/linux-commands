LINUX
## GIT and SETUP
`sudo apt install git` to install git

`cd`

`ssh-keygen -t rsa -b 4096 -C "name@email.com"`

`eval "$(ssh-agent -s)"` to start ssh-agent

`ssh-add .ssh/id_rsa` add a key

`xclip -selection clipboard < ~/.ssh/id_rsa.pub` copy to clipboard



#### Multiple Git SSH
`cd`

`ls -l ~/.ssh` to show list of ssh

`ssh-gen -t ed25519 -C "some names"` after pressing the enter, will be asked to enter dir

type `/home/pcname/.ssh/key_name` and press enter

`ssh-copy-id -i ~/.ssh/key_name.pub admin@skynet.learnlinux.cloud` to automatically add the ssh key to domain (optional)

`ssh -i ~/.ssh/key_name  ` to use specific ssh key

`eval $(ssh-agent)` to start ssh-agent

`ssh-add .ssh/id_rsa` add a key

`ssh key_name` to run the ssh



## NVM
`nvm ls-remote` show versions of node.js

`nvm ls` show downloaded versions of node.js

`nvm install node` will install the latest version of node.js

`nvm use node` uses the latest version

`nvm use 16.0.1` uses specific version of node.js

`nvm alias default 16.16.1` use the latest version as default

`nvm uninstall version` to uninstall specific version of node


