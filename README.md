# vagrant-lemp

edit your personal hosts file
```
sudo nano /etc/hosts
```
Add end of the file
```
192.168.56.101 awesome.test www.awesome.test
```

save and close

then install
```
vagrant plugin install vagrant-bindfs
```

go to folder you want it to save files
and pull files from git
```
git clone https://github.com/sserbest/vagrant-lemp.git
```
```
cd vagrant-lemp
```
```
unzip vagrant-lemp.zip
```
```
cd k4GkQp
```
```
vagrant up
```
```
vagrant ssh
```

IP: 192.168.56.101\
Domain: http://awesome.test/ \
www folder: your path/vagrant-lemp/k4GkQp/awesome/
/
### DB
DB Root Pass: 123\
DB User: dbuser (grant access)\
DB Pass: 123\
DB Name: dbname (test db)\
DB Engine: MariaDB\
/
Note: Connect using SSH tunnel, username vagrant and SSH key generated at puphpet/files/dot/ssh/id_rsa. This key is generated after your initial $ vagrant up!\

#### Bonus
I really liked Vagrant Manager, you should take a look.\
http://vagrantmanager.com/
