# hostapd-owrt-feed

## Как установить

1. Склонируйте этот репозиторий в любую папку:

   ```bash
   git clone git@github.com:legale/hostapd-owrt-feed.git
   cd hostapd-owrt-feed
   ```

2. Внутри него подготовьте исходники `src_git`, клон репозитория `legale/hostap`:

   ```bash
   cd hostapd
   git clone git@github.com:legale/hostap.git src_git
   cd src_git
   git switch wifi-fail-monitoring
   cd ..
   ```

Теперь `hostapd/src_git` содержит нужную ветку `wifi-fail-monitoring`, и можно продолжить сборку.
