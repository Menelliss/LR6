# LR6
Лабораторная работа №6
## Цель лабораторной работы: 
Изучение базовых возможностей системы управления версиями, опыт работы с Git Api, опыт работы с локальным и удаленным репозиторием.  
## Ход работы
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
git checkout -b report-branch  
