# coredns-docker

```sh
./etcdctl put /skydns/com/example/hoge '{"host":"192.168.1.254","port":8080,"ttl":3600}'
./etcdctl get /skydns/com/example/hoge
```

```sh
dig hoge.example.com @localhost -p 1053
```
