# AYANEO-AYASpace-Russian-Lang
AYANEO AYASpace 3.0 Russian Lang Руссификация 

https://www.ayaneo.com/support/download
AYASpaceGlobalSetup3.0.0.30.zip

Обновите файлы после установки AYASpace 3.0 из архива.




Bonus
Bazzite OS activated first display

Полный порядок действий:

1. Создайте каталог:
   ```bash
   mkdir -p ~/.config/environment.d
   ```
2. Откройте файл для редактирования:
   ```bash
   nano ~/.config/environment.d/gamescope-session-plus.conf
   ```
3. Введите содержимое:
   ```
   OUTPUT_CONNECTOR="eDP-1,*"
   ORIENTATION=left
   ```
4. Сохраните: Ctrl + O → Enter → Ctrl + X
5. Перезагрузитесь:
   ```bash
   reboot
   ```
