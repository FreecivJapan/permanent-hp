# freeciv常設鯖のwebページです。


## 起動例
sudo docker run -it --rm -p 80:80 -v /home/vagrant/hp/permanent-mainhp:/usr/local/apache2/htdocs -v /home/vagrant/hp/permanent-beginnerhp:/usr/local/apache2/htdocs/beginner httpd
