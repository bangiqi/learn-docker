# Implementasi Docker & Laravel

## Perkenalan Docker

Docker merupakan 

## Apa itu docker?

## Instalasi Docker

instalasi docker pada os arch linux

## Instalasi Docker Compose

instalasi docker pada os arch linux

## Instalasi Docker Machine

instalasi docker pada os arch linux

## Akses Docker dengan mysql client

untuk mengakses mysql yang terdapat didalam docker, dapat diakses dengan menggunakan perintah berikut :

``` bash
mysql -u root -p -h 172.19.0.2 -P 3306
```

- parameter <code>-u</code> digunakan untuk username akses mysql pada docker
- parameter <code>-p</code> digunakan untuk password pada docker
- parameter <code>-h</code> digunakan untuk hostname pada docker (disini menggunakan ip address)

- parameter <code>-P</code> untuk port yang digunakan untuk host

ip addres <code>172.19.0.2</code> yang digunakan sebagai hostname didapatkan dengan cara mengetik perintah

``` bash
sudo docker inspect [id_container] | grep IPAddress
```
maka akan tampil data berupa json.
cara untuk melihat container dengan menggunakan perintah

``` bash
sudo docker ps
```

result : 

## 500 Internal Server Error pada laravel

problem solving

``` bash
sudo chmod 755 -R [laravel_project]
chmod -R o+w laravel_blog/storage
```

## Referensi
- [Mysql docker containers understanding](http://stackoverflow.com/questions/31543175/getting-a-500-internal-server-error-on-laravel-5-ubuntu-14-04) 
- [500 Internal Server Error (stackoverflow)](http://stackoverflow.com/questions/31543175/getting-a-500-internal-server-error-on-laravel-5-ubuntu-14-04) 