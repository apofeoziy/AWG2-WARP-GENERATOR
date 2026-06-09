# Сгенерируйте конфиг Cloudflare WARP для AmneziaVPN
Этот bash скрипт сгенерирует конфиг Cloudflare WARP для AmneziaWG 2.0.

Не стоит выполнять его локально, так как РКН заблокировал запросы для получения конфига. Вместо этого лучше выполнять на удалённых серверах.

1. Заходим на https://terminator.aeza.net
2. Выбираем **`debian`**
3. Вставляем команду (Shift + Insert):
```bash
bash <(wget --inet4-only -qO- https://raw.githubusercontent.com/apofeoziy/AWG2-WARP-GENERATOR/main/warp_generator.sh)
```
4. После того, как конфиг сгенерируется, копируем его, либо скачиваем файлом по ссылке и импортируем в AmneziaVPN!👍

1. Заходим на https://pad.ws
2. Continue with Google
3. В окне Dashboard, если будет кнопка Start, нажмите на неё
4. Terminal
5. Вставляем команду (Shift + Insert):
```bash
bash <(wget --inet4-only -qO- https://raw.githubusercontent.com/apofeoziy/AWG2-WARP-GENERATOR/main/warp_generator.sh)
```
