https://www.maketecheasier.com/boot-recovery-mode-ubuntu/

https://forum.ubuntu.ru/index.php?topic=295709.0
https://habr.com/ru/post/315960/

wpa_cli
> add_network
> 
> set_network 0 ssid "Имя точки доступа"
> 
> set_network 0 key_mgmt WPA-PSK
> 
> set_network 0 pairwise CCMP
> 
> set_network 0 psk "Пароль"
> 
> enable_network 0


apt install xserver-xorg-input-all
