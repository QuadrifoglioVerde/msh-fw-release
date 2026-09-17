Repozitář s binárkami pro zařízení Meshtastic

Poslední verze:
- <a href="https://github.com/QuadrifoglioVerde/msh-fw-release/tree/main/firmware-2.8.0.8c14f65" target="_blank">v2.8.0</a>

Příkazy pro FAV Modul (pouze přes DM a uzel musí být ROUTER/ROUTER_LATE/CLIENT_BASE:
- FAV (vypíše seznam favoritů)
- FAV ADD !hexiduzlu (přidá uzel)
- FAV DEL !hexiduzlu (odebere uzel)
  Pro ADD/DEL je nutné mít klíč v adminu, FAV může vyžádat kdokoli

Postup instalace u ESP32:
- pokud na zařízení už Meshtastic je tak přes https://flasher.meshtastic.org/ nahrát podle HW verzi BEZ factory.bin
- Pokud není, tak nahrát originál přes tentýž web a pak postup výše.

Provedené úpravy:
- od 2.7.22 je telemetry min. na 1h u ROUTER(_LATE) (původně je 12h)
- od 2.7.19.9453f8d je NEIGHBORINFO zahrnuto v CORE PORTNUMS
- u RAK 4631 přidaná varianta pro LTO baterii
- Čas z GPS až je validní lokace 
- Možnost Neighbor Info přes LoRa na výchozím kanále
- Podpora češtiny na OLED - Znaková sada CS
- Telemetrie na MQTT dodržuje nastavene intervaly (nedocházi k prodlužování intervalů při využití kanálu, u MQTT nám jsou data fuk)




















