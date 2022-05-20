# Windows Subsystem Linux

## Allow `chmod` under mounted Windows drives

Add following to `/etc/wsl.conf`: 

```
[automount]
options = "metadata"
```

## Set up GCM for use with a WSL distribution

Run following command: 

```
git config --global credential.helper "/mnt/c/Program\ Files/Git/mingw64/libexec/git-core/git-credential-manager-core.exe"
```