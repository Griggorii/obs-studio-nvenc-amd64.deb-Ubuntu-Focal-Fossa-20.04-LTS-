# obs-studio-nvenc-amd64.deb-Ubuntu-Focal-Fossa-20.04-LTS-
obs-studio , deb , package , amd64.deb , nvenc

Run in folder obs-studio_23.2.3-1_amd64.deb

$$ sudo dpkg -i obs-studio_23.2.3-1_amd64.deb

Decklink Output support

My package replace obs , obs-studio , libobs0:amd64 , obs-plugins:amd64

Можно проверить так же работоспособность на ubuntu 19.04 , 19.10 и более низких версии в краинем случае если не запустится то вернуть исходную версию от своего дистрибутива командой ниже

$$ sudo apt purge obs-studio && sudo apt update && sudo apt --reinstall install obs-studio
