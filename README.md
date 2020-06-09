# ansible
private repository - dev machine setup automation via ansible

## recipe

``` bash
sudo apt install ansible keepassxc git
ssh-keygen -t rsa -b 4096 -C "some@email.com"
```

* retrieve keepass vault file from encrypted cloud storage
* login to github
* upload freshly generated ssh key


``` bash
cd $(HOME)
git clone git@github.com:tolry/ansible.git
cd ansible
cp config.dist.json config.json
vi config.json

./run
```
