

    git fetch https://git.codelinaro.org/clo/la/kernel/msm-4.9/ LA.UM.10.6.2.r1-02200-89xx.0

u can change msm-4.9 to your kernel version, e.g msm-4.14, msm-4.19
u can find LA.UM.XXXX from http://t.me/CLOReleases

Then to do the merge you just have to do

    git merge FETCH_HEAD

Now just fix the conflicts if there and then do

    git add -A
    
And

    git merge --continue
    
### Congratulation, you have (probably) succesfully merged a new caf tag.
