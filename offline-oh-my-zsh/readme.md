0) Before start, install git and zsh

`sudo apt-get install git-core zsh`


1) Go to the repository and download the zip file

[https://github.com/robbyrussell/oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh)


2) Open the zip file and extract to your home folder, and rename to .oh-my-zsh

`oh-my-zsh-master` -> `~/.oh-my-zsh`

3) Save the file `install-oh-my-zsh.sh` to your home folder, like `~/install-oh-my-zsh.sh`

4) Give permission to execute

`chmod +x install-oh-my-zsh.sh`

5) Run the script

`./install-oh-my-zsh.sh`

6) Set default sh

```
chsh -s `which zsh`
```

7) Restart!

`sudo shutdown -r 0`
