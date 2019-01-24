# How to make a cron task!
```bash
https://stackoverflow.com/a/14307712/9580001
```

## If you want your computer to say something on linux.
sudo apt-get install gnustep-gui-runtime && say "hello"

## Getting started

```bash
opens or creates crontab file ... this is where our cron tasks will live
crontab -e
```

```bash
/tmp/crontab.ypqenk/crontab <-- this is the file that crontab -e opens on linux
this works on mac too!

*/1 * * * * say "say my name, say my name"
*/1 * * * * echo "say my name, say my name" >> cron.log
*/1 * * * * $HOME/Desktop/file.sh

```

## To Remove:
```bash
crontab -e
```
comment out the lines of code with '#'

or remove the lines of code.
