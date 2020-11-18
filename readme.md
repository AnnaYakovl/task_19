1. Создана папка для виртуальной машины
2. В папке запущена команда
git clone https://github.com/laravel/homestead.git Homestead

3. В папке Homestead запущен init.bat
4. Исправлен файл Homestead.yaml (см. файл)
- имя машины: PHP_backend
- ip: 192.168.10.42
- настроен проброс папок и портов
5. В папке Homestead создана code/public
6. Запущен vagrant up
7. Виртуальная машина была создана (см. screenshot_1)
Порты проброшены (cм. screenshot_2)
Есть доступ через ssh (cм. screenshot_3)
8. Создан файл с приветствием, который открывается через браузер по application.local
(cм. screenshot_4)
9. Видим проброшенные папки на ВМ (cм. screenshot_5) с файлом init.php