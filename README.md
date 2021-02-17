# learn-docker

# cmd docker
### 1.	docker container ls
###     menampilkan docker image yang diaktifkan “running“
### 2.	docker container ls –all
###     menampilkan docker images yang dimiliki tidak running
### 3.	docker container start “mongoserver1“
###     mengaktifkan docker images yang dimiliki dengan “mongoserver1“ sebagai nama docker images yang akan diaktifkan
### 4.	docker container create –name “mongoserver1“ mongo:4.4.3
###     membuat docker images
### 5.	docker container rm “mongoserver2“
###     menghapus docker images
### 6.	docker container stop “mongoserver2“   
###     menghentikan docker images yang sedang berjalan
### 7.	docker images
###     menampilkan docker image yang dimiliki
### 8.	docker container create –name “mongoserver1” -p 8080:27017 “mongo:4.4.3”
###     membuat server docker container dapat diakses secara ekesternal di windows dari port docker container
### 9.	docker image rm “mongo:4.4.3”
###     menghapus docker image
### 10.	docker build –tag “app-golang:1.0” .
        membangun docker images yang dibuat sendiri
