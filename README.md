Poslední verze: <a href="https://github.com/QuadrifoglioVerde/msh-fw-release/tree/main/firmware-2.6.13.c2b52ee" target="_blank">v2.6.13</a>


Repozitář s binárkami pro zařízení Meshtastic

Provedené úpravy:
- Podpora GPS MTK 3329 (pMod GPS)
- Čas z GPS až je validní lokace 
- Možnost Neighbor Info přes LoRa na výchozím kanále
- Podpora češtiny na OLED - Znaková sada CS
- od 2.6.8 je ve FW přidaná podmínka should_report_location co brání mapreportu na MQTT, ta je zde odstraněna
- od 2.6.9 je omezena presnost pozice mapreportu, vraceno na stare hodnoty, uzivatel si snad sam muze rict co svetu povi a neni potreba mu neco vnucovat 🙄
