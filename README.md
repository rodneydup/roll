# roll
Simple bash script for rolling dice in the terminal

Download the script 'roll'
Put it in your path (usually `~/bin` on Linux, `/usr/local/bin` on MacOS)
Make it executable

Now you can use the command in your bash terminal.

Syntax:

`roll 5d6+10`

to roll 5 6-sided dice and add 10 to the result.

`roll` can also roll impossible dice:

`roll 200d79`


Quick install commands (copy into terminal):

### Linux

```
cd ~/bin
wget https://raw.githubusercontent.com/rodneydup/roll/master/roll
chmod +x roll
```

### MacOS

```
cd /usr/local/bin
wget https://raw.githubusercontent.com/rodneydup/roll/master/roll
chmod +x roll
```
