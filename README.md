# hostapd-owrt-feed

## Как установить

1. Склонируйте этот репозиторий в любую папку:

   ```bash
   git clone git@github.com:legale/hostapd-owrt-feed.git
   cd hostapd-owrt-feed
   ```

2. Внутри него подготовьте исходники `src_git`, клон официального репозитория hostapd/wpa_supplicant:

   ```bash
   cd hostapd
   git clone https://w1.fi/hostap.git src_git
   ```

Теперь `hostapd/src_git` содержит код из оригинального репозитория, и можно продолжить сборку.
