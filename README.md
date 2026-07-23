# Balance

> Una aplicació web minimalista i d'alt rendiment dissenyada per registrar i dividir despeses de manera fluida sense necessitat de bases de dades externes.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38BDF8?style=flat-square&logo=tailwind-css&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-222222?style=flat-square&logo=github&logoColor=white)

---

## Taula de Continguts

* [Sobre el Projecte](#-sobre-el-projecte)
* [Característiques Principals](#-característiques-principals)
* [Tecnologies Utilitzades](#-tecnologies-utilitzades)
* [Començar](#-començar)
* [Arquitectura del Projecte](#-arquitectura-del-projecte)
* [Guia d'Ús](#-guia-dús)
* [Privacitat i Persistència de Dades](#-privacitat-i-persistència-de-dades)
* [Contribució](#-contribució)
* [Llicència](#-llicència)

---

## Sobre el Projecte

**Balance** va néixer per eliminar la fricció a l'hora de registrar despeses compartides en sortides, sopars o petits viatges. Les aplicacions financeres tradicionals solen exigir registres d'usuari, servidors pesats o interfícies sobrecarregades.

Balance adopta un enfocament completament diferent: un tauler en mode fosc ultra-minimalista centrat exclusivament en la velocitat, la llegibilitat i la utilitat sense configuracions prèvies. Tot s'executa a l'instant directament al navegador.

---

## Característiques Principals

* **Agregació Financera en Temps Real:** Calcula automàticament els balanços totals i resumeix l'historial de transaccions a l'instant.
* **Formulari d'Entrada Ràpida:** Camps nets per a descripcions de transaccions, imports monetaris personalitzats i l'assignació de qui ha pagat.
* **Capa de Persistència Local:** Utilitza el `localStorage` del navegador per desar de manera segura les teues dades entre sessions, sense rastrejadors ni dependències del núvol.
* **Interfície Estètica Moderna:** Dissenyada amb una paleta refinada en tons zinc, vores suaus i difuminats de fons elegants.
* **Completament Responsiva:** Optimitzada tant per a pantalles de mòbil com per a monitors d'escriptori.

---

## Tecnologies Utilitzades

L'aplicació està estructurada en un sol fitxer per garantir la màxima portabilitat:

* **Estructura:** HTML5 semàntic
* **Estils:** Tailwind CSS (carregat via CDN) amb tipografia Inter
* **Lògica:** JavaScript Vanilla (mètodes d'arrays ES6+, renderització reactiva del DOM)

---

## Començar

No es requereix cap procés d'instal·lació, mòduls de Node ni variables d'entorn.

1. Clona o descarrega el repositori:
   ```bash
   git clone [https://github.com/el-teu-usuari/balance.git](https://github.com/el-teu-usuari/balance.git)
