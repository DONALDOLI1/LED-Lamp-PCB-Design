# 💡 LED Lamp PCB Design – T-Bulb
### Reproduction électronique et conception de circuits imprimés sous KiCad

🇫🇷 Français | 🇬🇧 English

---

# 🇫🇷 Version française

## 1. Présentation du projet

Ce projet porte sur la reproduction et la conception sous **KiCad EDA** du circuit électronique d'une lampe LED économique de type T-Bulb.

Le travail consiste à redessiner l'architecture électronique de la lampe et à concevoir les circuits imprimés correspondants. Il comprend notamment une carte d'alimentation et une carte destinée à recevoir les LED.

L'étude comprend également le routage des PCB et la préparation de panneaux regroupant plusieurs cartes, dans une perspective de fabrication.

**Il s'agit d'un travail de reproduction et de conception électronique, et non de la fabrication d'une lampe originale.**

## 2. Aperçu des conceptions

### 2.1. Conception des cartes électroniques

Les vues suivantes présentent différentes représentations des circuits imprimés étudiés.

| Vue générale de la conception | Vue de la carte rectangulaire |
|:---:|:---:|
| ![Vue générale](images/AMPOULE%20LED%20ECO-2.png) | ![Carte rectangulaire](images/AMPOULE%20LED%20ECO%20RECT-2.png) |

### 2.2. Panélisation des circuits imprimés

Les vues ci-dessous présentent les configurations de panneaux préparées dans le cadre de l'étude de panélisation.

| Configuration de panneau 1 | Configuration de panneau 2 |
|:---:|:---:|
| ![Panneau 1](images/AMPOULE%20LED%20ECO%20PANEL1-2.png) | ![Panneau 2](images/AMPOULE%20LED%20ECO%20PANEL-2.png) |

## 3. Caractéristiques techniques

| Paramètre | Description |
|---|---|
| Projet | Reproduction d'un circuit de lampe LED économique |
| Application | Éclairage LED de type T-Bulb |
| Logiciel de conception | KiCad EDA |
| Tension cible | 220–240 V AC |
| Alimentation étudiée | Capacitive, sans transformateur |
| Isolation galvanique | Absente |
| Redressement | Pont redresseur |
| Filtrage | Circuit de filtrage |
| Source lumineuse | 18 LED SMD |
| Organisation lumineuse | Matrice circulaire |
| Travail effectué | Conception et routage PCB |
| Panélisation | Configuration 12-en-1 étudiée |
| Fabrication physique | Non réalisée |
| Essais expérimentaux | Non réalisés |

## 4. Architecture électronique

Le système étudié repose sur deux ensembles complémentaires :

- **Carte d'alimentation (Driver) :** reproduction du circuit d'alimentation capacitive non isolée, avec redressement et filtrage.
- **Carte LED :** support de la matrice circulaire de 18 LED SMD.

Les deux cartes constituent l'architecture électronique de la lampe reproduite.

## 5. Travaux réalisés

- Reproduction du circuit électronique d'une lampe LED économique.
- Dessin et organisation des circuits sous KiCad.
- Conception des circuits imprimés.
- Routage des pistes.
- Préparation de configurations de panélisation.
- Étude d'un agencement de 12 cartes par panneau.

## 6. Outils et technologies

- KiCad EDA
- Conception de schémas électroniques
- Routage de circuits imprimés
- Électronique de puissance
- Éclairage LED
- Panélisation PCB

## 7. État d'avancement

- **Conception électronique :** réalisée.
- **Routage PCB :** réalisé.
- **Étude de panélisation :** réalisée.
- **Fabrication physique :** non réalisée.
- **Tests et validation expérimentale :** non réalisés.

Ce dépôt documente donc un travail de conception assistée par ordinateur. Il ne constitue pas une preuve de fonctionnement électrique ou de conformité à une norme de sécurité.

## 8. Avertissement de sécurité

**DANGER – SECTEUR 220–240 V AC**

La topologie étudiée utilise une alimentation capacitive sans isolation galvanique. Certaines parties du circuit peuvent donc être portées à un potentiel électrique dangereux.

Cette documentation est destinée à la présentation d'un travail de conception électronique.

Ne pas connecter une carte à une prise secteur et ne pas manipuler un circuit sous tension. Toute fabrication ou mise en service éventuelle nécessiterait une étude approfondie des protections, des distances d'isolement, de la dissipation thermique et de l'enveloppe de protection, ainsi qu'une validation par une personne qualifiée.

## 9. Concepteur

- **Conception et routage :** OLI OLI DONALD
- **Projet :** LED-Lamp-PCB-Design
- **Origine :** Cameroun 🇨🇲
- **Logiciel :** KiCad EDA

---

# 🇬🇧 English Version

## 1. Project Overview

This project focuses on reproducing and designing, using **KiCad EDA**, the electronic circuit of an energy-saving LED lamp of the T-Bulb type.

The work involves redrawing the lamp's electronic architecture and designing the corresponding printed circuit boards. It includes a power supply board and a board designed to accommodate the LEDs.

The study also covers PCB routing and the preparation of multi-board panels for potential manufacturing.

**This is an electronic reproduction and design project, not the development or physical manufacturing of an original lamp.**

## 2. Design Overview

### 2.1. Electronic Board Designs

| General design view | Rectangular board view |
|:---:|:---:|
| ![General view](images/AMPOULE%20LED%20ECO-2.png) | ![Rectangular board](images/AMPOULE%20LED%20ECO%20RECT-2.png) |

### 2.2. PCB Panelization

The following images show panel configurations prepared as part of the PCB panelization study.

| Panel configuration 1 | Panel configuration 2 |
|:---:|:---:|
| ![Panel 1](images/AMPOULE%20LED%20ECO%20PANEL1-2.png) | ![Panel 2](images/AMPOULE%20LED%20ECO%20PANEL-2.png) |

## 3. Technical Specifications

| Parameter | Description |
|---|---|
| Project | Reproduction of an energy-saving LED lamp circuit |
| Application | T-Bulb LED lighting |
| Design software | KiCad EDA |
| Target voltage | 220–240 V AC |
| Studied power supply | Transformerless capacitive supply |
| Galvanic isolation | None |
| Rectification | Bridge rectifier |
| Filtering | Filtering circuit |
| Light source | 18 SMD LEDs |
| LED arrangement | Circular matrix |
| Work completed | PCB design and routing |
| Panelization | 12-in-1 configuration study |
| Physical manufacturing | Not performed |
| Experimental testing | Not performed |

## 4. Electronic Architecture

The studied system is based on two complementary assemblies:

- **Power supply board (Driver):** reproduction of the non-isolated capacitive power supply circuit, including rectification and filtering.
- **LED board:** support for the circular array of 18 SMD LEDs.

Together, these boards form the electronic architecture of the reproduced lamp.

## 5. Work Completed

- Reproduction of an energy-saving LED lamp electronic circuit.
- Electronic drawing and organization using KiCad.
- Printed circuit board design.
- PCB track routing.
- Preparation of panelization configurations.
- Study of a 12-board-per-panel arrangement.

## 6. Tools and Technologies

- KiCad EDA
- Electronic schematic design
- PCB routing
- Power electronics
- LED lighting
- PCB panelization

## 7. Project Status

- **Electronic design:** completed.
- **PCB routing:** completed.
- **Panelization study:** completed.
- **Physical manufacturing:** not performed.
- **Experimental testing and validation:** not performed.

This repository documents a computer-aided electronic design project. It does not demonstrate electrical operation or compliance with safety standards.

## 8. Safety Warning

**DANGER – 220–240 V AC MAINS VOLTAGE**

The studied topology uses a capacitive power supply without galvanic isolation. Some parts of the circuit may therefore carry dangerous electrical potentials.

This documentation is intended to present an electronic design project.

Do not connect a board to a mains outlet or handle an energized circuit. Any potential manufacturing or commissioning would require a thorough assessment of electrical protection, insulation distances, thermal dissipation and protective enclosure design, as well as review by a qualified professional.

## 9. Designer

- **PCB Design and Routing:** OLI OLI DONALD
- **Project:** LED-Lamp-PCB-Design
- **Origin:** Cameroon 🇨🇲
- **Software:** KiCad EDA

---

*© OLI OLI DONALD – Educational electronic design project.*
