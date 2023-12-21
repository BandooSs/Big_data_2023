# Лабораторная работа №4 
## Задача: 
1. запустить ZooKeeper.  
Запуск произведен с помощью команды "zkServer.cmd".
2. Изучить директорию с установкой ZooKeeper.  
С помощью команды "ls /" получаем список узлов,  а также с помощью "create" создаем новые.
![График](https://github.com/BandooSs/Big_data_2023/blob/main/LR_4/images/1.png)
"stat /mynode" возращает метаданные узла:
![График](https://github.com/BandooSs/Big_data_2023/blob/main/LR_4/images/3.png)
Создаем два нумерованных узла в качестве дочерних mynode:
![График](https://github.com/BandooSs/Big_data_2023/blob/main/LR_4/images/4.png)  
5. Запустить интерактивную сессию ZooKeeper CLI и освоить её команды.
Проверьте в исходной консоли, что grue и bleen являются членами группы mygroup.
![График](https://github.com/BandooSs/Big_data_2023/blob/main/LR_4/images/5.png)  
7. Научиться проводить мониторинг ZooKeeper.
8. Разработать приложение с барьерной синхронизацией, основанной на ZooKeeper.
