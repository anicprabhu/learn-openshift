https://help.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh

ls -al ~/.ssh

clear

ssh-keygen -t rsa -b 4096 -C "prabhu.anic@gmail.com"

ls -al ~/.ssh

eval $(ssh-agent -s)

ssh-add ~/.ssh/id_rsa

clip < ~/.ssh/id_rsa.pub

ssh -T anicprabhu@github.com

ssh -T git@github.com

git push origin master

history

