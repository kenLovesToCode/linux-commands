LINUX
## GIT and SETUP
`sudo apt install git` to install git

`cd`

`ssh-keygen -t rsa -b 4096 -C "name@email.com"`

`eval "$(ssh-agent -s)"` to start ssh-agent

`ssh-add .ssh/id_rsa` add a key

`xclip -selection clipboard < ~/.ssh/id_rsa.pub` copy to clipboard





## NVM
`nvm ls-remote` show versions of node.js

`nvm ls` show downloaded versions of node.js

`nvm install node` will install the latest version of node.js

`nvm use node` uses the latest version

`nvm use 16.0.1` uses specific version of node.js

`nvm alias default 16.16.1` use the latest version as default

`nvm uninstall version` to uninstall specific version of node


