# sysbench

* https://github.com/akopytov/sysbenc

```bash
curl -s https://packagecloud.io/install/repositories/akopytov/sysbench/script.rpm.sh | sudo bash
sudo yum -y install sysbench
sysbench --test=cpu --cpu-max-prime=20000 run --time=3000
```
