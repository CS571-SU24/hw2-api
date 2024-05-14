build
```bash
docker build . -t ctnelson1997/cs571-su24-hw2-api
docker push ctnelson1997/cs571-su24-hw2-api
```

run
```bash
docker pull ctnelson1997/cs571-su24-hw2-api
docker run --name=cs571_su24_hw2_api -d --restart=always -p 38102:38102 -v /cs571/su24/hw2:/cs571 ctnelson1997/cs571-su24-hw2-api
```

**REMINDER: Use different `clazz.secret` files!!**

run fa
```bash
docker pull ctnelson1997/cs571-su24-hw2-api
docker run --name=cs571_fa_su24_hw2_api -d --restart=always -p 39102:38102 -v /cs571_fa/su24/hw2:/cs571 ctnelson1997/cs571-su24-hw2-api
```