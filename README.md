> [!WARNING]
>***!!! Не доделано и доделано не будет!!!***

[![Hits](https://hits.sh/github.com/ne3ep/obhod_rkn.svg?label=%D0%9F%D1%80%D0%BE%D1%81%D0%BC%D0%BE%D1%82%D1%80%D0%BE%D0%B2&color=13a6da&labelColor=0e5469)](https://hits.sh/github.com/ne3ep/obhod_rkn/)
# Начать с чего-то надо
Без лишних слов. 
1. Если вы вообще не знаете как обходить блокировки, кроме VPN с Play Маркета, то [тык сюда](https://github.com/ne3ep/obhod_rkn/main/README.md#1-%D0%BA%D0%B0%D1%82%D0%B5%D0%B3%D0%BE%D1%80%D0%B8%D1%8F).
2. Если у вас все работает и хочется улучшить/сделать постабильнее, то тык сюда. 
3. Если вы уже шарите и вам нужны всякие доки, скрипты и т.д., то тык сюда.

Разделение на категории существует только ради того, чтобы люди, знающие мало, не пытались использовать то, чего не понимают. Если вы хотите шарить больше, то гугл вам в помощь, хотя и я буду тоже где-то оставлять ссылки на обьяснения чего-либо.

<sub>Если есть предложения или исправления, открывайте Issue или Pull request.</sub>
# ДЛЯ ТЕХ КТО ВООБЩЕ НЕ ШАРИТ
Если мы знакомы — напишите мне в дискорде

Если нет, то либо соориентируйтесь в тексте ниже (сверху справа есть кнопочка с содержанием), либо платите продаваном по моей рефочке конечно же
- [БЕСПЛАТНО](https://t.me/waicorevpn_bot)
- [продаван 1](https://t.me/cult_vpnbot?start=partner_1483943788)
- [продаван 2](https://t.me/akenaivpn_bot?start=ref_1483943788)


# Дурилки DPI
Работают по принципу изменения сетевых пакетов, чтобы DPI системы на ТСПУ не могли по паттерну заблокировать данный пакет. Проще говоря, он просто обходит ЧАСТЬ ограничений со стороны ркн, то есть он не поможет, если: 
1. Иностранный сервис заблокировал доступ с российского IP
2. ркн заблокирован не домен, а IP-адресс

(YouTube и Discord работать будут)

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
## VLESS, VMESS и т.д.
Самый популярный прокси протокол на данный момент. Есть множество приложений под самые разные хотелки. Можно искать ключики и использовать бесплатно, но всё-таки советую настроить самостоятельно, арендовав VPS сервер, или купите подписку.

### Прокси-клиенты:
Приложения/программы, которые используются для подключения к прокси. Есть много ядер, но основных 3: Sing-Box, X-Ray и Mihomo. Люди, окромя пары процентов, разницы меж ними не заметят, так что используйте то приложение, которое вам предложили/нравится.
> [!TIP]
> ***Советую большинству Happ — [тык](https://github.com/Happ-proxy/happ-desktop).***
 
> [!WARNING]
>**При использовании Clash/Mihomo клиентов возможно большое потребление аккумулятора, так что сами решайте, что использовать на телефонах.**
#### **📱 Android**

‣ Mihomo:
- Clash meta for Android [GitHub](https://github.com/MetaCubeX/ClashMetaForAndroid/releases)
- FlClash [GitHub](https://github.com/chen08209/FlClash/releases)
- FlClashX [Github](https://github.com/pluralplay/FlClashX/)
- Clash Mi [GitHub](https://github.com/KaringX/clashmi)

‣ X-Ray:
- Happ [Google Play](https://play.google.com/store/apps/details?id=com.happproxy) [GitHub](https://github.com/Happ-proxy/happ-android/releases)
- OneXray [Google Play](https://play.google.com/store/apps/details?id=net.yuandev.onexray) [Github](https://github.com/OneXray/OneXray)
- V2rayNG [GitHub](https://github.com/2dust/v2rayNG/releases)
- V2Box [Google Play](https://play.google.com/store/apps/details?id=dev.hexasoftware.v2box)
- Simple GUI client by SaeedDev94 [GitHub](https://github.com/SaeedDev94/Xray)
- SimpleXray [GitHub](https://github.com/lhear/SimpleXray)

‣ Sing-Box:
- sing-box [Google Play](https://play.google.com/store/apps/details?id=io.nekohasekai.sfa) [GitHub](https://github.com/SagerNet/sing-box/releases)
- Husi [GitHub](https://github.com/xchacha20-poly1305/husi/releases)
- NekoBox [GitHub](https://github.com/MatsuriDayo/NekoBoxForAndroid/releases)
- Karing [GitHub](https://github.com/KaringX/karing/releases)
- Hiddify [Google Play](https://play.google.com/store/apps/details?id=app.hiddify.com) [GitHub](https://github.com/hiddify/hiddify-app/releases) (Нет обновлений с Октября 2024)

#### **📱 iOS**

‣ Mihomo:
- Clash Mi [AppStore](https://apps.apple.com/ru/app/clash-mi/id6744321968)

‣ X-Ray:
- Happ [AppStore](https://apps.apple.com/ru/app/happ-proxy-utility-plus/id6746188973)
- OneXray [AppStore](https://apps.apple.com/us/app/onexray/id6745748773) [Github](https://github.com/OneXray/OneXray)
- Streisand [AppStore](https://apps.apple.com/ru/app/streisand/id6450534064) 
- V2rayTun [AppStore](https://apps.apple.com/ru/app/v2raytun/id6476628951)
- V2Box [AppStore](https://apps.apple.com/ru/app/v2box-v2ray-client/id6446814690)

‣ Sing-box:
- sing-box [AppStore](https://apps.apple.com/ru/app/sing-box-vt/id6673731168)
- Hiddify [AppStore](https://apps.apple.com/us/app/hiddify-proxy-vpn/id6596777532) (Нет обновлений с Октября 2024)
- Karing [AppStore](https://apps.apple.com/ru/app/karing/id6472431552)

‣ Другое:
- Stash [AppStore](https://apps.apple.com/ru/app/stash-rule-based-proxy/id1596063349) [Wiki](https://stash.wiki/) ($7)
- ShadowRocket [AppStore](https://apps.apple.com/ru/app/shadowrocket/id932747118) ($3)
- Loon [AppStore](https://apps.apple.com/ru/app/loon/id1373567447?platform=iphone) ($8)

#### **💻 Windows**

‣ Mihomo:
- FlClashX [Github](https://github.com/pluralplay/FlClashX/)
- Koala Clash  [Github](https://github.com/coolcoala/clash-verge-rev-lite)
- Prizrak-Box [GitHub](https://github.com/legiz-ru/Prizrak-Box)
- Clash Verge [GitHub](https://github.com/clash-verge-rev/clash-verge-rev/releases)
- FlClash [GitHub](https://github.com/chen08209/FlClash/releases)
- Clash Mi [GitHub](https://github.com/KaringX/clashmi)

‣ X-Ray:
- V2rayN [GitHub](https://github.com/2dust/v2rayN/releases)
- OneXray [Github](https://github.com/OneXray/OneXray)
- Happ [GitHub](https://github.com/Happ-proxy/happ-desktop/releases)

‣ Sing-box:
- Karing [GitHub](https://github.com/KaringX/karing/releases)
- NekoRay от throneproj [GitHub](https://github.com/throneproj/Throne/releases)
- Hiddify [GitHub](https://github.com/hiddify/hiddify-app/releases) (Нет обновлений с Октября 2024)

#### **🐧 Linux**

‣ Mihomo:
- FlClashX [Github](https://github.com/pluralplay/FlClashX/)
- Koala Clash [Github](https://github.com/coolcoala/clash-verge-rev-lite)
- Prizrak-Box [GitHub](https://github.com/legiz-ru/Prizrak-Box)
- FlClash [GitHub](https://github.com/chen08209/FlClash/releases)
- Clash Verge [GitHub](https://github.com/clash-verge-rev/clash-verge-rev/releases)

‣ X-Ray:
- V2rayN [GitHub](https://github.com/2dust/v2rayN/releases)
- OneXray [Github](https://github.com/OneXray/OneXray)

‣ Sing-box:
- NekoRay от throneproj [GitHub](https://github.com/throneproj/Throne/releases)
- Hiddify [GitHub](https://github.com/hiddify/hiddify-app/releases) (Нет обновлений с Октября 2024)

### Откуда брать ключи
Ключ — это ссылка deeplink формата, в которую входят данные для подключения. Либо вводиться вручную, либо благодаря системе подписок автоматом парсится из обычной ссылки. Можно взять как бесплатно, так и за платно
#### Бесплатно
- [TG Bot](https://t.me/waicorevpn_bot)(лучше всех нижних)
- [GitHub repo 1](https://github.com/Epodonios/v2ray-configs)
- [GitHub repo 2](https://github.com/kort0881/vpn-key-vless)
- [GitHub repo 3](https://github.com/AvenCores/goida-vpn-configs)
- [GitHub repo 4](https://github.com/NiREvil/vless)
- [GitHub repo 5](https://github.com/MatinGhanbari/v2ray-configs)

#### Платно
Для тех, кто может и желает 150-200 рублей в месяц платить за безопасность и отсуствие лишних телодвжиений. 
Здесь вы можете выбрать 2 пути: 
1. Аренда VPS сервера от 100-150 рублей и 5 минут потыкаться в терминале
2. Покупка подписки у третьих лиц
   
Я всем советую именно ручную настройку, но так как много кто пугается любого терминала, оставлю ссылки и на вторых. Также необходимо учитывать плюсы и минусы каждого из вариантов:

|  | Аренда VPS | Покупка подписки |
|----------|-----------|-----------|
|✅Плюсы |Часто дешевле<br>Знаешь как работает<br>Можно настроить под себя|Сразу несколько серверов<br>Без заморочек|
|❌Минусы |Только 1 сервер(аптайм 100% нереален)<br>Необходимо скопировать пару команд в терминал| Часто дороже<br>Много откровенного говна<br>Вместе с тобой на этом сервере сидит половина Сызрани|

##### Аренда VPS
Первым делом необходимо найти хостинг. Самое сложное в этом деле. Есть тысячу разных обзоров и отзывов, но каждый выбирает ТОЛЬКО по своему настроению. 

Ниже будет тир лист МОЕГО мнения о том или ином хостинге, так как какого-то объективного топа нет и быть не может, а необходимость помочь самым маленьким в этом деле есть. Если вы НЕ согласны с тем или иным местом, то этот тирлист был написан не для вас. Свое мнение можете оставить в этом [ТГК](https://t.me/hosterobzorgroup).
|Сойдет|Не знаю/не рыбо не мясо|Не стоит брать|
|-----------|-----------|-----------|
|[u1host](https://u1host.com/?from=190)<br>|||

## <img src="/data/unsecure.svg" alt="Logo" width="30"> SOCKS 4/5
Очень древний прокси протокол, который работает только благодаря его распространенности среди корпоративных сетях и т.п. Стоит рассматривать как ЗАПАСНОЙ ВАРИАНТ на всякий случай, так как БЕЗОПАСНЫМ ЕГО НАЗВАТЬ НИКАК НЕЛЬЗЯ.
Можно:
- Вручную взять данные для подключения и подключиться.

  Способы подключения:
    - в настройках — [тык](https://support.google.com/pixelphone/answer/9655181?hl=ru#zippy=%2C%D0%BA%D0%B0%D0%BA-%D0%BD%D0%B0%D1%81%D1%82%D1%80%D0%BE%D0%B8%D1%82%D1%8C-%D0%BF%D1%80%D0%BE%D0%BA%D1%81%D0%B8-%D1%81%D0%B5%D1%80%D0%B2%D0%B5%D1%80-%D0%BD%D0%B0-%D1%83%D1%81%D1%82%D1%80%D0%BE%D0%B9%D1%81%D1%82%D0%B2%D0%B5)
    - через [приложение 1](https://play.google.com/store/apps/details?id=com.scheler.superproxy)
    - через [приложение 2](https://play.google.com/store/apps/details?id=com.elseplus.tun2socks)
  
    <sub>Приложений куча, выбирайте то, которое нравится вам</sub>
    
  Откуда взять данные для подключения: 
    - [GitHub repo 1](https://github.com/TheSpeedX/PROXY-List)
    - [GitHub repo 2](https://github.com/proxifly/free-proxy-list)
    - [GitHub repo 3](https://github.com/hookzof/socks5_list)
    - [GitHub repo 4](https://github.com/databay-labs/free-proxy-list)
    - [Telegram 1](https://t.me/Socks_Proxy_List)
    - [Telegram 2](https://t.me/freeproxysocks5)
- Скачать готовое приложения из Play Market, которое с вероятностью 96% работать не будет
# Источники
1. [ТГК Обсуждение VPN-протоколов](https://t.me/protocol_vpn)
2. 
>надо дописать список хостингов, добавить тг впн продавцов, написать свой гайд по влесс на 3хуя, марз и ремну, про нынешний тип блокировок влесс, сделать переходники
