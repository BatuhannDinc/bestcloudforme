# BC4M Case

Python ile geliştirilmiş olan uygulamanın container üzerinde çalışıtırılması.

## Kullanım 

Repoyu locale kopyalar

```bash 
    git clone https://github.com/BatuhannDinc/bestcloudforme.git
```

Docker image oluşturur

```bash 
    docker build -t batuhandinc/bestcloudforme:v1 .
```

Oluşturulan image ı dockerhub'a gönderir

```bash 
    docker push batuhandinc/bestcloudforme:v1 
```

Bu image dan docker container yaratır

```bash 
    docker container run -d -p 5000:5000 batuhandinc/bestcloudforme:v1
```

Tarayıcıda test etmek için

```bash 
    http://localhost:5000
```
