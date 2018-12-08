# VPSD
VPSD bash script

# Установка
1. Создаём пользователя vpsop или другого (нужно указать в настройках)
2. Создаём каталог /scripts
3. Кидаем в него данные скрипты
4. Ставим права на запуск
5. Создаём синволическую ссылку: ln -s /scripts/vmnet /etc/qemu-ifup
6. Создаём синволическую ссылку: ln -s /scripts/vmnet /etc/qemu-ifdown
7. Создаём синволическую ссылку: ln -s /scripts/vmnet /scripts/antispoof
