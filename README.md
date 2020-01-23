# Rails Setup
## clone repo

```
git clone https://github.com/medicharlachiranjeevi/Rails-new-project.git
```
### First install zsh
```

cd Rails-new-project/setup-zsh/
```

#### [install zsh](setup-zsh/)

### Second install node and yarn
```

cd Rails-new-project/setup-node/
```

### Third install ruby and rbenv
```
sudo apt -y install curl dirmngr apt-transport-https lsb-release ca-certificates
curl -sL https://deb.nodesource.com/setup_12.x | sudo -E bash -
sudo apt -y install nodejs
sudo apt -y  install gcc g++ make
curl -sL https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -
echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list
sudo apt-get update && sudo apt-get install yarn
sudo apt install -y  software-properties-common  python  python3  zip  curl  htop  rsync  unzip  wget  postgresql  libpq-dev  autoconf   bison   build-essential   libssl-dev   libyaml-dev   libreadline6-dev   zlib1g-dev   libncurses5-dev   libffi-dev    libgdbm-dev  redis-server  docker.io  zsh  wget  git   nginx  default-jdk  nodejs 

```

#### [install ruby and rbenv](setup-rbenv/)

### Start new project on rails

#### [latest ruby and rails](new-Project/)
