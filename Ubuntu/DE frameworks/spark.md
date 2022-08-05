### Installation of Debian packages for ROS 2 Humble Hawksbill in Ubuntu Jammy

Install wget
```
apt-get install wget
``` 

Go to ```https://spark.apache.org/downloads.html``` and choose the version you want to Install


Copy the recommended link in redirected page

```
wget {url}
```

Extract it
```
tar -xvf spark-x.x.x-bin-hadoopx.x.tgz
```

```cd ~```

Add the path to source file

```
gedit ~/.bashrc
```

```
SPARK_HOME={Path_to_the_file}
export PATH=$PATH:$SPARK_HOME/bin:$SPARK_HOME/sbin
```

```
source ~/.bashrc
```sssssssssssssssssssssssssssssssssssssssssssssssssssssssssssssssss