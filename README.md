# Домашнее задание по MySQL  
**Гаран Степан**

## Тема: Установка MySQL, создание пользователя, импорт базы данных Sakila

---

## Задание 1. Установка MySQL Server и Workbench

1. Запускаю инсталлятор MySQL Installer.  
2. Выбираю установку MySQL Server и MySQL Workbench.  
3. Прохожу стандартные шаги установки.

**Скриншот установки:**

![](01_mysql_install.png)
---

## Задание 2. Подготовка MySQL Workbench

Открываю MySQL Workbench — начальное окно пустое.

**Скриншот пустого окна Workbench:**

![](02_workbench_empty.png)
---

## Задание 3. Попытка создать пользователя `sys_temp`

Ввожу команду:

```sql
CREATE USER 'sys_temp'@'localhost'
IDENTIFIED WITH mysql_native_password BY 'TempPass123!';
Скриншот попытки создания:
![]03_workbench_editor_empty.png
