# freeciv常設鯖のwebページです。

## ビルド方法
sudo docker build -t sensu-watson/freeciv-hp .

## 起動例
sudo docker run -dit --rm -p 80:80 -v [YourFilePath]/permanent-mainhp:/usr/local/apache2/htdocs -v [YourFilePath]/permanent-beginnerhp:/usr/local/apache2/htdocs/beginner -v [YourFreecivFilePath]/docker-home:/usr/local/apache2/htdocs/freeciv-data-5556 -v [YourHiddenFreecivFilePath]/docker-home:/usr/local/apache2/htdocs/freeciv-data-5557 sensu-watson/freeciv-hp 
