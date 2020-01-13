/etc/ansible/host
ansible 192.168.1.129 -m ping -u orion


execute
$ansible-playbook -i hosts playbook.yml -b -K

systemctl
sudo systemctl start nginx 
sudo systemctl stop nginx 
sudo systemctl restart nginx

sudo service nginx start
sudo service nginx stop
sudo service nginx restart

sudo /etc/init.d/nginx start
sudo /etc/init.d/nginx stop
sudo /etc/init.d/nginx restart

