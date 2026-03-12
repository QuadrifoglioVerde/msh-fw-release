Repozitář s binárkami pro zařízení Meshtastic

Poslední verze:
- <a href="https://github.com/QuadrifoglioVerde/msh-fw-release/tree/main/firmware-2.7.20.79ac40e" target="_blank">v2.7.20</a>

Postup instalace u ESP32:
- pokud na zařízení už Meshtastic je tak přes https://flasher.meshtastic.org/ nahrát podle HW verzi BEZ factory.bin
- Pokud není, tak nahrát originál přes tentýž web a pak postup výše.

Provedené úpravy:
- od 2.7.19.9453f8d je NEIGHBORINFO zahrnuto v CORE PORTNUMS
- u RAK 4631 přidaná varianta pro LTO baterii
- Čas z GPS až je validní lokace 
- Možnost Neighbor Info přes LoRa na výchozím kanále
- Podpora češtiny na OLED - Znaková sada CS
- Telemetrie na MQTT dodrzuje nastavene intervaly




















