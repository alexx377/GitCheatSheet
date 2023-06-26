# Шпаргалка по базовым командам Linux и Git
## Команды Linux
---
```bash
pwd
cd <каталог>
mkdir
touch
cp <что> <куда>
mv <что> <куда>
rm
rmdir
rm -r
ls <каталог>
ls -a <каталог>
ls -l <каталог>
ls -la <каталог>
```
## Настройка Git
---
```bash
git config --global user.name "<Имя>"
git config --global user.email "<Почта>"
git config --global init.defaultBranch main
```
## Работа с репозиторием
```bash
git init
git add <список файлов>
git add --all
git commit -m "<Исходящее сообщение>"
git status
git log
git remote add origin <URL-репозитория>
git push -u origin main
git push
```
## Создание SSH-ключей
```bash
ssh-keygen -t ed25519 -C "электронная почта, к которой привязан ваш аккаунт на GitHub" 
ssh-keygen -t rsa -b 4096 -C "электронная почта, к которой привязан ваш аккаунт на GitHub" 
```