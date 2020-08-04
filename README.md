# configure-ssh-key
Configuring git bash with git hub account

1. Create account on github
2. Install gitbash in your system
3. open git bash
4. ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
5. eval $(ssh-agent -s)
6. ssh-add ~/.ssh/id_rsa
7. clip < ~/.ssh/id_rsa.pub
8. Open gitHub > Settings > Add SSH Key > paste it.
****************************************** Done *********************************************
