# wsl-azure-bash-terminal
Inspired by the terminal that Jessical Dean configured, I put my own spin on it. Similar to hers but more geared towards the things that I'm currently using.

## Process

### Pre-reqs
- Windows 10 Fall Creators Edition
- Ubuntu installed (https://docs.microsoft.com/en-us/windows/wsl/install-on-server)

### Install
```
bash -c "$(curl -fsSL https://raw.githubusercontent.com/jerry-locke/wsl-azure-bash-terminal/vsCodeconfigure.sh)"
```

### Post Install Config

Start bash and edit your bash file.

```
bash
vim ~/.zshrc
```

Change ZSH_THEME from robbyrussell to cloud and save the file

Start zsh:
```
zsh
```

### Troubleshooting
If you are not able to see the proper icons in vsCode - you might need to fix your registry HKCU:\Console settings. Clearing that resolved the issue for me, but you might have settings in there that you want to keep, so make sure you know what you want to remove and keep a backup of your registry / registry key before making any changes.
