WebRTC позволяет передавать потоковые данные между браузерами пользователей по технологии «точка-точка» (p2p) для таких областей применения, как потоковое воспроизведение аудио и видео. При использовании  возможно раскрытие реального IP пользователя, в т. ч. локального (за NAT) посредством протокола STUN. Причём, де-анонимизация адреса может происходить даже при использовании прокси и TOR/VPN-соединений. Утечка DNS-адреса также имеет место быть.

Тестирование на утечку ip-адреса.

- https://whoer.net/
- https://ipleak.net/
- https://diafygi.github.io/webrtc-ips/
- https://www.browserleaks.com/webrtc
- https://www.ip-secrets.com/
- https://www.perfect-privacy.com/webrtc-leaktest/
- https://hidester.com/webrtc-ip-leak-test/
- https://net.ipcalf.com/
- https://ip.voidsec.com/

https://www.webrtc-experiment.com/DetectRTC/

А ещё проверить включён или выключен WebRTC в браузере можно тут:
http://tools.add0n.com/webrtc-leakage.html
и
http://tools.add0n.com/what-is-my-ip.php

Требуется пояснение.
> Следует учесть, однако, что защита от утечки IP-адреса в WebRTC с помощью расширений — не самый надежный метод. В некоторых случаях браузер все равно будет передавать IP-адрес. Для дополнительной надежности можно установить расширение ScriptSafe или uMatrix, которые блокируют вообще все скрипты в браузере.
