Repozitář s binárkami pro zařízení Meshtastic

Poslední verze:
- <a href="https://github.com/QuadrifoglioVerde/msh-fw-release/tree/main/firmware-2.6.13.edbf1f6" target="_blank">v2.6.13</a>
- <a href="https://github.com/QuadrifoglioVerde/msh-fw-release/tree/main/firmware-2.7.1.e804ab1" target="_blank">v2.7.1</a>

Postup instalace u ESP32:
- pokud na zařízení už Meshtastic je tak přes https://flasher.meshtastic.org/ nahrát podle HW *-update.bin
- Pokud není, tak nahrát originál přes tentýž web a pak postup výše.

! POZOR: 2.7.0 na některých ESP32 padá !

Provedené úpravy:
- Čas z GPS až je validní lokace 
- Možnost Neighbor Info přes LoRa na výchozím kanále
- Podpora češtiny na OLED - Znaková sada CS
- výchozí MQTT server je mqtt.aperturelab.cz
