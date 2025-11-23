[![Hits](https://hits.sh/github.com/ne3ep/obhod_rkn.svg?label=%D0%9F%D1%80%D0%BE%D1%81%D0%BC%D0%BE%D1%82%D1%80%D0%BE%D0%B2&color=13a6da&labelColor=0e5469)](https://hits.sh/github.com/ne3ep/obhod_rkn/)
# Начать с чего-то надо
Без лишних слов. 
1. Если вы вообще не знаете как обходить блокировки, кроме VPN с Play Маркета, то тык сюда.
2. Если у вас все работает и хочется улучшить/сделать постабильнее, то тык сюда. 
3. Если вы уже шарите и вам нужны всякие доки, скрипты и т.д., то тык сюда.

Разделение на категории существует только ради того, чтобы люди, знающие мало, не пытались использовать то, чего не понимают. Если вы хотите шарить больше, то гугл вам в помощь, хотя и я буду тоже где-то оставлять ссылки на обьяснения чего-либо.

<sub>Если есть предложения или исправления, открывайте Issue или Pell request.</sub>

# Дурилки DPI
Работают по принципу изменения сетевых пакетов, чтобы DPI системы на ТСПУ не могли по паттерну заблокировать данный пакет. Проще говоря, он просто обходит ЧАСТЬ ограничений со стороны ркн, то есть он не поможет, если: 
1. Иностранный сервис заблокировал доступ с российского IP
2. ркн заблокирован не домен, а IP-адресс

(то есть YouTube и Discord работать будут)

Также DNS сервера провайдеров часто не резолвят домены заблокированных сайтов, поэтому используйте какой-либо другой DNS сервер.
## [zapret](https://github.com/bol-van/zapret) (for PC)
Можно сказать единственная программа на ПК, которая стоит вашего внимания, так как остальные проги либо перестали обновлятся (GoodByePDI) или является малоизвестны.

### Для 1 категории людей
- Программа с красивым интерфейсом — [тык на скачивание](https://github.com/youtubediscord/zapret/releases), [тык на гайд](https://github.com/youtubediscord/zapret/wiki/%D0%93%D0%BB%D0%B0%D0%B2%D0%BD%D0%BE%D0%B5-%D0%BC%D0%B5%D0%BD%D1%8E)
- Подобранные конфиги от Вашего любмого ютубера — [тык на скачивание](https://howdyho.net/windows-software/discord-fix-snova-rabotayushij-diskord-vojs-zvonki), [тык на гайд](https://www.youtube.com/watch?v=MR06Nmmr3Fc)
### Для 2 категории людей
- Подобранные конфиги с настройкой только для YouTube, Discord и CloudFlare — [тык](https://github.com/Flowseal/zapret-discord-youtube)
- Сборка для Windows от разраба — [тык](https://github.com/bol-van/zapret-win-bundle)
### Для 3 категории людей
Хз что вам писать, по поводу запрета, но пару ссылок хотя бы покидаю
- Для любимого пингвина на десктоп — [тык](https://github.com/kartavkun/zapret-discord-youtube) или [тык](https://github.com/Sergeydigl3/zapret-discord-youtube-linux)
- Скрипт для VPS серверов — [тык](https://github.com/IndeecFOX/zapret4rocket)

## [ByeByeDPI](https://github.com/romanvht/ByeByeDPI) (Android)
Основное приложение по типу дурилок DPI на Android
- Скачать — [тык](https://github.com/romanvht/ByeByeDPI/releases)
- Гайд — [тык](https://github.com/BDManual/ByeByeDPI-Manual/blob/main/start.md)

## Дополнение
Установка zapret на роутер, чтобы на все устройства сразу работало:
- на OpenWRT — [тык](https://github.com/remittor/zapret-openwrt)
- на Keenetic OS — [тык](https://telegra.ph/Nastrojka-zapret-ot-bol-van-na-Keentic-04-27)

Ну и из-за уважения к Vakdik`у:
- GoodByeDPI — [тык](https://github.com/ValdikSS/GoodbyeDPI)

# VPN и Proxy
В чем разница? [Ответ](https://habr.com/ru/articles/829282/)

Основной способ обхода блокировок, работающий при всех типах блокировки, кроме некоторых исключений, про которые я, надеюсь, не забуду написать. 
## <img src="/data/unsecure.svg" alt="Logo" width="30"> SOCKS 4/5
Очень древний прокси протокол, который работает только благодаря его распространенности среди корпоративных сетях и т.п. Стоит рассматривать как ЗАПАСНОЙ ВАРИАНТ на всякий случай, так как БЕЗОПАСНЫМ ЕГО НАЗВАТЬ НИКАК НЕЛЬЗЯ.
### Бесплатно
- Вручную взять данные для подключения и подключиться.

  Способы подключения:
    - в настройках — [тык](https://support.google.com/pixelphone/answer/9655181?hl=ru#zippy=%2C%D0%BA%D0%B0%D0%BA-%D0%BD%D0%B0%D1%81%D1%82%D1%80%D0%BE%D0%B8%D1%82%D1%8C-%D0%BF%D1%80%D0%BE%D0%BA%D1%81%D0%B8-%D1%81%D0%B5%D1%80%D0%B2%D0%B5%D1%80-%D0%BD%D0%B0-%D1%83%D1%81%D1%82%D1%80%D0%BE%D0%B9%D1%81%D1%82%D0%B2%D0%B5)
    - через [приложение 1](https://play.google.com/store/apps/details?id=com.scheler.superproxy)
    - через [приложение 2](https://play.google.com/store/apps/details?id=com.elseplus.tun2socks)
  
    <sub>Приложений куча, выбирайте то, которое нравится вам</sub>
  Откуда взять данные для подключения: (
    - [GitHub repo 1](https://github.com/TheSpeedX/PROXY-List)
    - [GitHub repo 2](https://github.com/proxifly/free-proxy-list)
    - [GitHub repo 3](https://github.com/hookzof/socks5_list)
    - [GitHub repo 4](https://github.com/databay-labs/free-proxy-list)
    - [Telegram 1](https://t.me/Socks_Proxy_List)
    - [Telegram 2](https://t.me/freeproxysocks5)
- Всякие приложения из Play Marketa сами найти сможете
