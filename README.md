# php-fpm-nginx-hello
*ini adalah contoh docker untuk php + fpm + nginx*

Ambil file dari github: 
```
git clone https://github.com/imanwibisono/php-fpm-nginx-hello.git
```
Build Docker Image: 
```
docker build -t php-fpm-nginx-hello .
```
Jalankan Docker: 
```
docker run -d -p host_port:80 php-fpm-nginx-hello
```
