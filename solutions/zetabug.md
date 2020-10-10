#### Task 1
```
# Created Audio directory
$ mkdir Audio

# Changed path to Audio directory
$ cd Audio/

# Created 10 audio files with given format
$ touch Song{1..10}.mp3

# Moved audio files to Music directory
$ mv * ~/Music

# Created symbolic link between Audio and Music directory
$ ln -s ~/Music ~/Audio

```
#### Task 2
 ```
 # Created users rob and bob
 $ sudo useradd -m bob -p bob
 $ sudo useradd -m rob -p rob
 
 # Created group sysadmin
 $ sudo groupadd sysyadmin
 
 # Added rob and bob to group sysadmin
 $ sudo usermod -a -G sysadmin bob
 $ sudo usermod -a -G sysadmin rob

# Created group manager
$ sudo groupadd manager

# Added rob and bob to group manager
$ sudo usermod -a -G manager rob
$ sudo usermod -a -G manager bob

# Created user max
$ sudo useradd -m max -p max

# Added max to group sysadmin
$ sudo usermod -a -G sysadmin max

