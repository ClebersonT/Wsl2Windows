# Windows Wsl2

Open powerShell
```bash
wsl --install
```
If you see the help text run wls --list --online to list available distros

Set default WSL version in powerShell
```bash
wsl --set-default-version 2
```

Install distro
```bash
wsl --install -d <distro Name>
 ```

Set default Linux distribution
```bash
wsl --set-default <Distribution Name>
```

Open Terminal Distro Linux
```bash
sudo apt update
```

Install Node:

Using Ubuntu
```bash 
curl -fsSL https://deb.nodesource.com/setup_16.x | sudo -E bash -
sudo apt-get install -y nodejs 
```

Using Debian
```bash 
curl -fsSL https://deb.nodesource.com/setup_16.x | bash -
apt-get install -y nodejs
```
