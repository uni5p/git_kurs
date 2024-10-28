# ��� ��� ��������� �� Git

## ���������

git config --list<br>
git config --global uset.name "asdasd" <br>
git config --global uset.email "3423423@3423423.456"<br>

## ������� �����������

git init

##���� �� �������� ������� Git-������������ �� �� �����, � ����� �����������. ��� ����� ����� ������� ������� �������� .git

$ cd <����� � ������������> * ������� � �����* <br>
$ rm -rf .git *������� �������� .git*   <br>

## ������� ��������� �����������.

git status

## �������� ����� � ����������� � ������������

$ git add --all # ����������� � ���������� ��� ����� � �����������  <br>
$ git status # ��������� ������ <br>

##������� ��������

git log


## ���������� �� ��������� SSH-�����

$ ssh-keygen -t ed25519 -C "����������� �����, � ������� �������� ��� ������� �� GitHub" <br>
��� <br>
$ ssh-keygen -t rsa -b 4096 -C "����������� �����, � ������� �������� ��� ������� �� GitHub" <br>

## �������� �����

ls -a ~/.ssh

## ����� � ��������
[������](https://code.s3.yandex.net/git_Basic/SSH_Screencast.mp4 "https://code.s3.yandex.net")


## ��������� �������� ����������� � ���������� � git remote add

$ cd ~/dev/first-project <br>
$ git remote add origin git@github.com:%���_��������%/first-project.git  <br>

## ���������, ��� ����������� �������,
� git remote -v  <br>

## ��������� ��������� �� �������� �����������

 ������ ��������
$ git push -u origin main # ���� ������� ������� � ������, ����������<br>
                          # �������� main �� master.<br>




