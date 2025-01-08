# Initial Configuration

## Git install & Config

<code> sudo apt install git  </code> <br>
<code> git config --global init.defaultBranch main </code> <br>
<code> git config --global user.name "carobte" </code> <br>
<code> git config --global user.email "caro.bustamante.escobar@gmail.com" </code> <br>

![imagen](https://github.com/user-attachments/assets/6bd3b30f-7d8c-4e3f-b729-5d2bafddb6be)


## Node js with NVM

### NVM
<code> sudo apt install curl </code> <br>
<code> curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.0/install.sh </code> <br>
<code> source ~/.bashrc </code> <br>
<code> nvm --version </code> <br>

### Nodejs
<code> nvm install 23 </code> <br>
<code> node -v </code> <br>
<code> nvm current </code> <br>

![imagen](https://github.com/user-attachments/assets/541f321a-225a-4d11-8f85-c3bea0252b2e)


## .Net

### SKD

<code> sudo apt-get update && \  sudo apt-get install -y dotnet-sdk-8.0 </code> <br>

### Runtime

<code> sudo apt-get update && \
  sudo apt-get install -y aspnetcore-runtime-8.0 </code> <br>

![imagen](https://github.com/user-attachments/assets/85d2432e-7b48-4a25-9afa-5bab22fb4e30)

## Laravel & Composer

<code> /bin/bash -c "$(curl -fsSL https://php.new/install/linux/8.4)" </code>
<code> composer global require laravel/installer </code>
<code> laravel new example-app </code> 

## PostgresQL and pgAdmin

1. sudo apt update
2. sudo apt upgrade
2. sudo apt install postgresql
3. curl https://www.pgadmin.org/static/packages_pgadmin_org.pub | sudo apt-key add -
sudo sh -c 'echo "deb https://ftp.postgresql.org/pub/pgadmin/pgadmin4/apt/$(lsb_release -cs) pgadmin4 main" > /etc/apt/sources.list.d/pgadmin4.list && apt update'
4. sudo apt install pgadmin4
5. sudo apt install pgadmin4-desktop (only for web)
6. sudo apt install pgadmin4-web (only for desktop)
7. sudo /usr/pgadmin4/bin/setup-web.sh
8. sudo snap install pgadmin4

sudo systemctl enable postgresql -> Starts with the system.


![imagen](https://github.com/user-attachments/assets/bbcd9f4b-6894-48d7-a1bb-635b3233978e)


## Postman
sudo snap install postman

![imagen](https://github.com/user-attachments/assets/08818376-7d45-45a3-9f66-d7821432f3cd)































