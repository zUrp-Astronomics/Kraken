<!-- zurp-readme-header:begin — paste this block once, never again: the poster and the badges update themselves at each build of the site — do not edit it -->
<div align="center">

<a href="https://zurp-astronomics.github.io/kraken/"><img src="https://zurp-astronomics.github.io/brand/posters/kraken.webp" alt="zUrp Astronomics product poster" width="420"></a>

![status](https://img.shields.io/endpoint?url=https%3A%2F%2Fzurp-astronomics.github.io%2Fbrand%2Fstatus%2Fkraken.json)

</div>

<!-- zurp-readme-header:end -->

# Kraken — USB-3 PowerBox

# ⚠Work in Progress -NOT VALIDATED- don't build it⚠

 small but efficient powerbox for astronomy setup

## Une PowerBox de poche qui déborde

#### Specs actuelles
* PCB 85x56mm, la taille d'un raspberry pi
* boitier 90x60x24mm, 130cm3 (contre 170 pour la Pegasus Pocket Powerbox Advance Gen2)
* ESP32, et peut-être un écran OLED 128x64 ...
* capteur T° et humidité externe, sur un jack (à définir)
* face BOT full CMS assemblé, face TOP connecteurs + capas
* Connecteur alim XT60, 12V / 20A, 250W max
* Connexion hôte USB3 type B
* 2x USB3 / 2.5A, 3x USB2 /2.5A, 1x USB2 5A
* 2 sorties DC_2.1 12V 3A ON/OFF
* 2 sorties pilotables DC_2.1 12V 3A ou Adj 3-10V / 4A
* 2 sorties pilotables USB (alim uniquement) Adj 1-5V 2A


![3D_view](9_Assets/kraken_powerbox_3D.png)

## Arborescence

| dossier | contenu |
|---|---|
| [`0_Datasheets/`](0_Datasheets/) | datasheets des composants |
| [`9_Assets/`](9_Assets/) | images des README et de la doc ; vitrine du site (`zurp.yml` + affiche) |

## Licences

- Logiciel : [`LICENSE`](LICENSE)
- Matériel : [`LICENSE-HARDWARE`](LICENSE-HARDWARE)
