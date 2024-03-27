# sp


## Описание [09.03.2007]

1. Данный комплект, состоящий из трех элементов учебной системы программирования
и тестового задания:
    - компилятор    PL/1 --> Ассемблер   ( komppl.c ),
    - компилятор    Ассемблер --> объектный образ  ( kompassr.c ),
    - абсолютный загрузчик, эмулятор и отладчик ( absloadm.c ),
    - тестовое задание ( examppl.pli и spismod ).
    
2. Для получения исполняемых модулей двух компиляторов и абсолютного загрузчика
следует выполнить Bash-скрипт GenSysProgr.

3. После получения исполняемого кода компиляторов можно запускать на выполнение
тестовый пример с помощью Bash-скрипта StartTestTask.


## Подготовка

1. 32-х разрядный Ubuntu 14:
    - Виртуалки:
        - [VirtualBox (VDI)][uwuntu14-vb]
        - [VMware (VMDK)][uwuntu14-vmdk]
    - Установочные образы:
        - [Desktop][uwuntu14-desktop]
        - [Server][uwuntu14-server]

2. Пакет libncurses5-dev:

    `sudo apt update && sudo apt install -y libncurses5-dev`


[uwuntu14-desktop]: https://www.releases.ubuntu.com/14.04/ubuntu-14.04.6-desktop-i386.iso

[uwuntu14-server]: https://www.releases.ubuntu.com/14.04/ubuntu-14.04.6-server-i386.iso

[uwuntu14-vb]: https://sourceforge.net/projects/osboxes/files/v/vb/55-U-u/14.04/14.04.6/1404.632.7z/download

[uwuntu14-vmdk]: https://sourceforge.net/projects/osboxes/files/v/vm/55-U--u/14.04/14.04.6/14-04632.7z/download
