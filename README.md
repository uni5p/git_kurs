# Это моя шпаргалка по Git

## настройка

git config --list<br>
git config --global uset.name "asdasd" <br>
git config --global uset.email "3423423@3423423.456"<br>

## создать репозитарий

git init

##Если вы случайно сделали Git-репозиторием не ту папку, её можно «разгитить». Для этого нужно удалить скрытую подпапку .git

$ cd <папка с репозиторием> * перешли в папку* <br>
$ rm -rf .git *удалили подпапку .git*   <br>

## текущее состояние репозитория.

git status

## добавить файлы в репозитарий к отслеживанию

$ git add --all # подготовили к сохранению все файлы в репозитории  <br>
$ git status # проверили статус <br>

##История коммитов

git log


## Инструкция по генерации SSH-ключа

$ ssh-keygen -t ed25519 -C "электронная почта, к которой привязан ваш аккаунт на GitHub" <br>
или <br>
$ ssh-keygen -t rsa -b 4096 -C "электронная почта, к которой привязан ваш аккаунт на GitHub" <br>

## Проверка ключа

ls -a ~/.ssh

## видео с примером
[ссылка](https://code.s3.yandex.net/git_Basic/SSH_Screencast.mp4 "https://code.s3.yandex.net")


## Привязать удалённый репозиторий к локальному — git remote add

$ cd ~/dev/first-project <br>
$ git remote add origin git@github.com:%ИМЯ_АККАУНТА%/first-project.git  <br>

## Убедиться, что репозитории связаны,
— git remote -v  <br>

## Отправить изменения на удалённый репозиторий

 Первая отправка
$ git push -u origin main # Если команда приведёт к ошибке, попробуйте<br>
                          # заменить main на master.<br>




