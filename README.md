# how-to

personal memos on how to do stuff

**fix ubuntu bluetooth**
```
mv ~/.config/pulse/ ~/.config/pulse.old systemctl --user restart pulseaudio
```

**switch branch**

the working tree and the index are updated to match the branch

all new commits will be added to the tip of this branch
```
git switch -c <new-branch>
```
