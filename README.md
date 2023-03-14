# Инструкция установки через докер

- заходим на VM по sftp под пользователем admin
- загружаем папки `deploy` и `src` файлы в /home/admin/
- заходим на VM по ssh и выполняем команду


```sh
cd /home/admin/;
sudo chmod +x ./deploy/setup.sh; 
sudo /home/admin/deploy/setup.sh;
```
