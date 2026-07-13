---
title: "Firmware frissítés"
author: rain-it
date: 2026-07-13 06:00:00 +0200
categories: [RainIT, Firmware frissítés]
tags: [RainIT, Firmware frissítés]
pin: false
img_path: '/assets/img/20260713'
---


## Bevezetés

A RainIT firmware-e időről időre frissül: új funkciók, hibajavítások és kompatibilitási fejlesztések kerülnek bele. A vezérlő OTA (levegőn keresztüli) frissítést támogat, vagyis a firmware közvetlenül a webes felületen keresztül feltölthető, külön kábel vagy programozó nélkül.


## Mentés frissítés előtt

Frissítés előtt mindig érdemes elmenteni a beállításokat, hogy hiba esetén gyorsan vissza lehessen állítani a programokat és a konfigurációt. Ezt az oldalsávon található **Konfiguráció exportálása** menüponttal lehet megtenni.

Fontos különbség a verziószámozásban:
- **Pontozott verzióváltás** (pl. 2.2.0 → 2.2.1) gyári visszaállítást indít, és **minden beállítás törlődik**.
- **Build szám változás** (pl. 2.2.1(2) → 2.2.1(4)) esetén **minden beállítás megmarad**.


## OTA frissítés lépései

1. Töltsd le a megfelelő firmware fájlt (`.bin` formátum) a <a href="https://github.com/repa6/OpenSprinkler-Firmware/releases">letöltési oldalról</a>. A legfrissebb verzió mindig az oldal tetején található.
2. Nyiss meg egy böngészőt, és írd be a `http://vezerlo-ip/update` címet, ahol a `vezerlo-ip` a vezérlőd hálózati IP-címe.
   - Az IP-cím a router felületén érhető el.
   - Ha a vezérlő WiFi AP (hozzáférési pont) módban van, csatlakozz a kijelzőn megjelenő SSID-hez, ilyenkor a frissítő oldal a `http://192.168.4.1/update` címen érhető el.
3. A frissítő oldalon válaszd ki a `.bin` fájlt, add meg a vezérlő jelszavát, majd küldd el.
4. Várd meg, amíg a folyamat lefut – a vezérlő a frissítés végeztével automatikusan újraindul.
   - Ha a feltöltés nem sikerül, próbáld meg újra.
   - Ha a vezérlő lefagy, húzd ki, majd dugd vissza a tápot, és próbáld újra.


## Gyakori problémák és megoldásuk

- **Jelszóhiba AP módban:** ha a jelszó nem működik, próbáld meg helyette annak MD5-hash értékét megadni (például az `opendoor` jelszó MD5-hash-e `a6d82bced638de3def1e9bbb4983225c`). <a href="https://rain-it-md5.vercel.app">Rain-IT online MD5 kalkulátor ide kattintva érhető el.</a>
- **Sérült firmware / a vezérlő nem indul el:** ha a frissítés után a vezérlő nem indul el, USB-soros programozóval újra fel kell írni a firmware-t (ebben szívesen segítek).
