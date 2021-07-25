# roll
A simple bash script for rolling dice in the terminal

roll v1.1 features:
- Roll arbitrary numbers of arbitrarily-sided dice
- Add or subtract modifier to/from final result
- Set a minimum result for each rolled die

Download the script 'roll'  
Put it in your path (usually `~/bin` on Linux, `/usr/local/bin` on MacOS, ?? on Windows)  
Make it executable

Now you can use the command in your bash-compatible terminal.

![](roll.mp4)

## Example Usage

`roll 3d15`

will roll 3 15-sided dice

        
`roll 5d6+10`

will roll 5 6-sided dice and add 10 to the total result

`roll 7d203-11`

will roll 7 203-sided dice and subtract 11 from the total result

`roll 6d10+12 -min 6`

will roll 6 10-sided dice, rounding up to 6 any individual die that results in less than 6, and then add 12 to the total result.


## Quick install commands (copy into terminal)

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
### Windows

???
