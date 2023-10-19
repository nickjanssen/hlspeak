# hlspeak

Play Half-Life 1 sounds straight from your terminal! Great for letting you know when CI builds finish and for pranking you friends with self-destruct timers.

## Installation
```
mkdir ~/.hlspeak
cd ~/.hlspeak
git clone git@github.com:sourcesounds/hl1.git .
git clone git@github.com:nickjanssen/hlspeak.git .
chmod +x hlspeak
echo 'export PATH=$PATH:~/.hlspeak' >> ~/.bashrc && source ~/.bashrc
```

# Usage

```
hlspeak five minutes remaining
```

```
hlspeak detonation in three two one
```

For the female variant, use the `-f` parameter.

```
hlspeak -f power_level_is ninety percent
```
