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
 # Created users rob,bob and max
 $ sudo useradd -m bob -p bob
 $ sudo useradd -m rob -p rob
 $ sudo useradd -m max -p max
 
 # Created group sysadmin and manager
 $ sudo groupadd sysyadmin
 $ sudo groupadd manager
 
 # Added rob,bob and max to group sysadmin
 $ sudo usermod -a -G sysadmin bob
 $ sudo usermod -a -G sysadmin rob
 $ sudo usermod -a -G sysadmin max

 # Added rob and bob to group manager
 $ sudo usermod -a -G manager rob
 $ sudo usermod -a -G manager bob



 

