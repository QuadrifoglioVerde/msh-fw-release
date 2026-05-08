Repozitář s binárkami pro zařízení Meshtastic

Poslední verze:
- <a href="https://github.com/QuadrifoglioVerde/msh-fw-release/tree/main/firmware-2.7.23.acf2635" target="_blank">v2.7.23</a>

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




















