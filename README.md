# how-to

personal memos on how to do stuff

fix ubuntu bluetooth
```
mv ~/.config/pulse/ ~/.config/pulse.old systemctl --user restart pulseaudio
```

Switch to a specified branch. The working tree and the index are updated to match the branch. All new commits will be added to the tip of this branch.
```
git switch -c <new-branch>
```
