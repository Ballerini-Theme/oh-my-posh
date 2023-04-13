### [Oh My Posh](https://ohmyposh.dev/)

For this theme to work well, you must have a [nerd font](https://www.nerdfonts.com/) installed.

#### Install using Git

If you are a git user, you can install the theme by running the command in the desired folder:

- Bash/Zsh

```sh
git clone https://github.com/dreisss/oh-my-posh.git && shell="$(oh-my-posh get shell)" && echo "eval \"\$(oh-my-posh init $shell --config $(pwd)/oh-my-posh/ballerini.omp.json)\"" >> ~/.$(echo $shell)rc
```

- Powershell (Administrator)

```ps1
git clone https://github.com/dreisss/oh-my-posh.git; Set-ExecutionPolicy -Scope LocalMachine Bypass -Force; echo "oh-my-posh init pwsh --config \"$(pwd)\oh-my-posh\ballerini.omp.json\" | Invoke-Expression" >> $PROFILE
```

After this, reload your profile for the changes to take effect.
