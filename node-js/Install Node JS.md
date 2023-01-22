## HOWTO : Install Node JS

1) On Windows
2) On MacOS
3) On Linux Distributions
4) Using Version Managers (Advanced but highly recommended)

### 1. On Windows

- Visit Node JS's official website https://nodejs.org/en/
- Click on "Downloads" button in the top bar
- Select your prefered version "Long term support - LTS (Recommended for most users)" or "Current Latest"
- Click on "Windows Installer"
- Once the installer downloads, run it and complete the setup

### 2. On MacOS 

- Visit Node JS's official website https://nodejs.org/en/
- Click on "Downloads" button in the top bar
- Select your prefered version "Long term support - LTS (Recommended for most users)" or "Current Latest"
- Click on "macOS Installer"
- Once downloaded, run the pkg to install node

### 3. On Linux Distributions

#### Arch Linux

```
sudo pacman -S nodejs npm
```

#### Red Hat Based Distributions

- These include CentOS, RHEL and Fedora
```
sudo dnf module install nodejs:<stream>
```
- Example
```
sudo dnf module install nodejs:18/common
```
- To find out the list of all available streams
```
sudo dnf moodule list nodejs
```

#### For Debian and Ubuntu and derivatives

- It is not recommended to install node with apt package manager
- Please follow the instructions on https://github.com/nodesource/distributions/blob/master/README.md

### 4.  Using Version Managers

%%link the article on version managers here%%

For all other ways of installing node, please visit https://nodejs.org/en/download/package-manager/#debian-and-ubuntu-based-linux-distributions