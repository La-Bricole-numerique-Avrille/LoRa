# LoRa

LoRaWAN est un protocole de communication radio qui définit comment des équipements terminaux communiquent sans fil au travers de passerelles, constituant ainsi un réseau étendu à basse consommation (LPWAN).
Il est basé sur la technologie de modulation propriétaire LoRa, créée en 2009 par la start-up grenobloise Cycléo, et rachetée par l'entreprise américaine Semtech en 2012.

## Modules

Pour démarrer avec Meshtastic, vous devez d’abord acquérir un matériel compatible:
- [Heltec WiFi LoRa 32(V3)](https://heltec.org/project/wifi-lora-32-v3/)
- [LILYGO Lora T3S3 v1.0](https://meshtastic.org/docs/hardware/devices/lilygo/lora/?t-lora=S3-v1)
- [LILYGO TTGO T-Beam Devices](https://meshtastic.org/docs/hardware/devices/lilygo/tbeam/?t-beam=sx1262)

La liste complète se trouve ici : [Supported Hardware Overview](https://meshtastic.org/docs/hardware/devices/)


## Meshtastic

Meshtastic est un projet qui vous permet d’utiliser des radios LoRa bon marché comme moyen de communication à longue portée et hors réseau pour les zones sans service cellulaire fiable. Chaque membre du réseau maillé peut envoyer et voir des messages texte et activer des fonctionnalités de localisation, rendant ce système particulièrement utile pour les groupes évoluant dans des zones éloignées.

### Articles

- F4HXN.fr : Meshtastic : [La Communication Hors Réseau pour Tous](https://www.f4hxn.fr/meshtastic-la-communication-hors-reseau-pour-tous/)
- Framboise 314 : [Connaissez-vous le réseau MESHTASTIC ? et sa version GAULIX ?](https://www.framboise314.fr/connaissez-vous-le-reseau-meshtastic-et-sa-version-gaulix/)
  - [Présentation de MESHTASTIC](https://www.framboise314.fr/meshtastic-presentation/)
  - [De quoi j’ai besoin ?](https://www.framboise314.fr/meshtastic-de-quoi-jai-besoin/)
  - [ISM, LoRa et LoRaWAN](https://www.framboise314.fr/meshtastic-ism-lora-et-lorawan/)
  - [Protocole MQTT](https://www.framboise314.fr/meshtastic-protocole-mqtt/)
  - [Matériel Disponible (Aout 2024)](https://www.framboise314.fr/meshtastic-materiel-disponible-aout-2024/)
  - [Démarrer en Meshtastic](https://www.framboise314.fr/meshtastic-demarrer-en-meshtastic/)
  - [Installer Meshtastic sur un module](https://www.framboise314.fr/meshtastic-installer-meshtastic-sur-un-module/)
  - [Configurer le module via la connexion USB](https://www.framboise314.fr/meshtastic-configurer-le-module-via-la-connexion-usb/)

### Installation du firmware

- [Meshtastic Web Flasher](https://flasher.meshtastic.org/)

**Heltec WiFi LoRa 32(V3)**

- Presser et maintener le bouton `PRG` de la carte tout en branchant le câble USB sur le PC pour basculer en mode boot.

![image](https://github.com/user-attachments/assets/9ec98a84-7b37-4d7c-91c2-5a2c5f65abc0)

### Configuration

**Interface web**

- https://client.meshtastic.org/

- Selectionner la région correspondant à la bande de fréquence (ici 868 Mhz) puis enregistrer
- Le module redémarre pour prendre en compte les modifications
 
![image](https://github.com/user-attachments/assets/d14684b1-3f26-4cf7-a1cb-d08d4d06f9dd)

**Rôles**

![image](https://github.com/user-attachments/assets/888357ef-06b5-407b-b54e-5cb934271bfc)

### Application smartphone

- [Application Android](https://play.google.com/store/apps/details?id=com.geeksville.mesh&pli=1)
- [Application iOS](https://meshtastic.org/docs/category/apple-apps/)


