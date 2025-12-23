Repozitář s binárkami pro zařízení Meshtastic

Poslední verze:
- <a href="https://github.com/QuadrifoglioVerde/msh-fw-release/tree/main/firmware-2.7.17.f9ea1c9" target="_blank">v2.7.17</a>

Postup instalace u ESP32:
- pokud na zařízení už Meshtastic je tak přes https://flasher.meshtastic.org/ nahrát podle HW verzi BEZ factory.bin
- Pokud není, tak nahrát originál přes tentýž web a pak postup výše.

Návod jak na Wi-Fi OTA u ESP32 <a href="https://github.com/QuadrifoglioVerde/msh-wifi-ota" target="_blank">ZDE</a>

Provedené úpravy:
- u RAK 4631 přidaná varianta pro LTO baterii
- Čas z GPS až je validní lokace 
- Možnost Neighbor Info přes LoRa na výchozím kanále
- Podpora češtiny na OLED - Znaková sada CS
- Telemetrie na MQTT dodrzuje nastavene intervaly











