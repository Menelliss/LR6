# LR6
Лабораторная работа №6
## Цель лабораторной работы: 
Изучение базовых возможностей системы управления версиями, опыт работы с Git Api, опыт работы с локальным и удаленным репозиторием.  

## Ход работы

### Операции
$ git log --pretty=format:"%h - %ad - %an: %s" --date=short
07faf1f - 2023-11-08 - Menelliss: Added progress 2
d38191a - 2023-11-08 - Menelliss: Added progress
0e7a404 - 2023-11-08 - Menelliss: The file was deleted
09f82f6 - 2023-11-08 - Menelliss: Resolved the conflict
6ca65ac - 2023-11-08 - Menelliss: Add files via upload
921f53b - 2020-11-21 - Kurtyanik: Обновление информации
0f9f50d - 2020-11-21 - Kurtyanik: Заполнил файл
c08a654 - 2020-11-21 - Kurtyanik: Файл создан пустым
3c6e913 - 2020-11-21 - Kurtyanik: Initial commit

### Лог команд
cd d:  
cd SUAI  
git clone https://github.com/Menelliss/LR6  
cd LR6  
git pull  
git log  --all  
git log -n 1  
git merge origin/branch1  
git status  
cat mergefile.txt  
git add .  
git commit -m "Resolved the conflict"  
git push origin -d branch1  
git add .  
git commit -m "The file was deleted"  
git add .  
git commit -m "Added text"  
git reset --hard HEAD^  
git checkout -b new_branch  
git add .  
git commit -m "Added progress 1" 
git add .  
git commit -m "Added progress 2"  
git log --pretty=format:"%h - %ad - %an: %s" --date=short
git push origin new_branch
 
### Изображения
Изображение консоли  
![Первый скриншот](https://github.com/Menelliss/LR6/raw/new_branch/screen/Screenshot1.png)  

Изображения консоли  
![Второй скриншот](https://github.com/Menelliss/LR6/raw/new_branch/screen/Screenshot2.png)  

Изображения консоли  
![Третий скриншот](https://github.com/Menelliss/LR6/raw/new_branch/screen/Screenshot3.png)  

Изображения консоли  
![Четвертый скриншот](https://github.com/Menelliss/LR6/raw/new_branch/screen/Screenshot4.png)  

## Вывод: 
Я изучила базовые возможности системы управления версиями, получила опыт работы с Git Api и опыт работы с локальным и удаленным репозиторием.  