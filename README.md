Repozitář s binárkami pro zařízení Meshtastic

Poslední verze:
- <a href="https://github.com/QuadrifoglioVerde/msh-fw-release/tree/main/firmware-2.7.7.2260081" target="_blank">v2.7.7</a>

Postup instalace u ESP32:
- pokud na zařízení už Meshtastic je tak přes https://flasher.meshtastic.org/ nahrát podle HW *-update.bin
- Pokud není, tak nahrát originál přes tentýž web a pak postup výše.

Provedené úpravy:
- u RAK 4631 přidaná varianta pro LTO baterii (testujeme)
- Čas z GPS až je validní lokace 
- Možnost Neighbor Info přes LoRa na výchozím kanále
- Podpora češtiny na OLED - Znaková sada CS
