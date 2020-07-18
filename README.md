# Undiscord

Short bash script that reopens discord on crash.


I'm having an issue where discord randomly crashes, so I made a script to restart it when it crashes.
It's not a perfect solution but it works in most cases.
One major annoyance is that on startup discord steals focus 3 times and that can interrupt whatever you're doing.

you can set up undiscord.sh as an executable or you can also just run this in the command line:
```bash
while true; do discord && break; done
```

If that doesn't work, you can also try:
```bash
while true; do discord; done
```
which will just reopen discord regardless of whether or not it crashes, so you'll have to stop the script if you want to close it

BTW, this script should work with pretty much any program, just replace discord with the executable that you want to reload on crash.

credit goes to this stackexchange thread:
https://askubuntu.com/questions/572820/re-run-an-application-script-when-it-crashes
