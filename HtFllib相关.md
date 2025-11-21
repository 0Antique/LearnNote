[https://github.com/TsingZ0/HtFLlib](https://github.com/TsingZ0/HtFLlib)

```shell
python -u main.py -t 3 -ab 1 -lr 0.01 -jr 1 -lbs 10 -ls 1 -nc 20 -ncl 100 -data Cifar100 -m HtFE-img-8 -fd 512 -did 2 -algo FML -al 0.5 -bt 0.5 > total-Cifar100-HtFE-img-8-fd=512-FML.out
```



### 运行FML
可以运行

```shell
python main.py -lr 0.01 -jr 1 -m HtFE-img-8 -algo FML -data Cifar10 -ncl 10 -al 0.9 -bt 0.1 -lbs 1024 -gr 50
```



```shell
python main.py -algo FML -data Cifar10 -ncl 10 -m HtFE-img-8 -lbs 1024 -gr 50 --aware_alpha 0.5 --aware_project 0
```

![](https://cdn.nlark.com/yuque/0/2025/png/27683841/1754656842045-faf470ab-1c9f-4308-91b7-7768c3d1945a.png)

