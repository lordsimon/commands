
Linux
==============
Ctrl – Alt – T to open Terminal
netstat -ntulp

vim /etc/apt/sources.list.d/10gen.list

sudo apt-get update

ssh server
---------
sudo apt-get install openssh-server				
gksu gedit /etc/ssh/sshd_config
You could limit the IP Address SSH Server communicates on by uncommenting ( # ) line ListenAddress  x.x .x.x and specifying the IP Address.


Git
======
http://nathanj.github.com/gitguide/index.html

git remote add origin https://github.com/username/Hello-World.git
Creates a remote named "origin" pointing at your GitHub repo


git push origin master
Sends your commits in the "master" branch to Git
========