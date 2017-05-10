# jmeter-docker



#To start the master

```
sudo docker run -dit --name master nkooinga/jmmaster /bin/bash
```

#To start slaves

```
sudo docker run -dit --name slave01 nkooinga/jmserver /bin/bash
sudo docker run -dit --name slave02 nkooinga/jmserver /bin/bash
sudo docker run -dit --name slave03 nkooinga/jmserver /bin/bash
```
# jmeter-docker
