# smfetch
A simple fetch tool with less than 150 lines of code.

## About the project
Just a simple fetch tool that I wrote with less than 150 lines. To be honest, I didn't pay attention to the aesthetics and quality of the code. While writing the code, I paid particular attention to the fact that there were no dependencies. Because my goal was to make software that works directly when the repository is cloned, without the need for anything.

### Installation steps
Doesn't require things like make, clone the repository and run.
```bash
git clone https://github.com/agahemir/smfetch
cd smfetch/
chmod +x ./smfetch
./smfetch
```
### Screenshots
![Alt text](https://i.imgur.com/9qXK0Ix.png "Screenshot")

If you have bugs in the code or suggestions for improving the code, submit a pull request. I usually update the code on sundays. 

### What works and what doesn't
The commands are for the linux kernel. Make sure lspci, uname, whoami commands are running on the system. Currently there is support for ASCII art for 7 distributions. However, the script can run on Debian, Arch, Ubuntu, Fedora, OpenSUSE, Alpine and Gentoo or others. (others not tested)

Special thanks to me0wing-katto for his help with this code :)
