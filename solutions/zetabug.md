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

