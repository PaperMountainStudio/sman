# sman
simple `man` command written in shell

# Install
```sh
git clone https://github.com/PaperMountainStudio/sman
cd sman
cp sman /usr/local/share/bin/
```
If you want to use sman using command `man`:
```sh
ln -s /usr/local/share/bin/man /usr/local/share/bin/sman
```

# Usage
Show man page for `sh`
```sh
sman sh
```
Show man page for `sh` in section 1
```sh
sman 1 sh
```
