# Installation of Debian packages for ROS 2 Humble Hawksbill in Ubuntu Jammy

To check locale which supports UTF-8

Install locale
```
sudo apt update && sudo apt install locales
sudo locale-gen en_US en_US.UTF-8
sudo update-locale LC_ALL=en_US.UTF-8 LANG=en_US.UTF-8
export LANG=en_US.UTF-8
``` 

```
apt-cache policy | grep universe
```

```
sudo apt install software-properties-common
sudo add-apt-repository universe
```

```
sudo apt update && sudo apt install curl gnupg lsb-release
sudo curl -sSL https://raw.githubusercontent.com/ros/rosdistro/master/ros.key -o /usr/share/keyrings/ros-archive-keyring.gpg
```

```
echo "deb [arch=$(dpkg --print-architecture) signed-by=/usr/share/keyrings/ros-archive-keyring.gpg] http://packages.ros.org/ros2/ubuntu $(source /etc/os-release && echo $UBUNTU_CODENAME) main" | sudo tee /etc/apt/sources.list.d/ros2.list > /dev/null
```

```
sudo apt update
```

```
sudo apt upgrade
```

```
sudo apt install ros-humble-desktop
```

# Install Gazebo for ROS 2 Humble Hawksbill in Ubuntu Jammy
```
sudo apt-get update
```

```
sudo apt-get -y install gazebo

```
