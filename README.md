# Initial Configuration for Ubuntu - Riwi

## Git install & Config

- <code> sudo apt install git  </code> <br>
- <code> git config --global init.defaultBranch main </code> <br>
- <code> git config --global user.name "carobte" </code> <br>
- <code> git config --global user.email "caro.bustamante.escobar@gmail.com" </code> <br>

## Node js with NVM

### NVM
- <code> sudo apt install curl </code> <br>
- <code> curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.0/install.sh </code> <br>
- <code> source ~/.bashrc </code> <br>
- <code> nvm --version </code> <br>

### Nodejs
- <code> nvm install 23 </code> <br>
- <code> node -v </code> <br>
- <code> nvm current </code> <br>

## .Net

### SKD

- <code> sudo apt-get update && \  sudo apt-get install -y dotnet-sdk-8.0 </code> <br>

### Runtime

- <code> sudo apt-get update && \
  sudo apt-get install -y aspnetcore-runtime-8.0 </code> <br>

## Laravel & Composer

- <code> /bin/bash -c "$(curl -fsSL https://php.new/install/linux/8.4)" </code> <br>
- <code> composer global require laravel/installer </code> <br>
- <code> laravel new example-app </code> <br> 

## PostgresQL and pgAdmin

- <code> sudo apt update </code> <br>
- <code> sudo apt upgrade </code> <br>
- <code> sudo apt install postgresql </code> <br>
- <code> curl https://www.pgadmin.org/static/packages_pgadmin_org.pub | sudo apt-key add -
sudo sh -c 'echo "deb https://ftp.postgresql.org/pub/pgadmin/pgadmin4/apt/$(lsb_release -cs) pgadmin4 main" > /etc/apt/sources.list.d/pgadmin4.list && apt update' </code> <br>
- <code> sudo apt install pgadmin4 </code> <br>
- <code> sudo apt install pgadmin4-desktop (only for web) </code> <br>
- <code> sudo apt install pgadmin4-web (only for desktop) </code> <br>
- <code> sudo /usr/pgadmin4/bin/setup-web.sh </code> <br>
- <code> sudo snap install pgadmin4 </code> <br>

For postreSQL server start with system:
- <code> sudo systemctl enable postgresql </code> <br>

## Postman
- <code> sudo snap install postman </code> <br>
