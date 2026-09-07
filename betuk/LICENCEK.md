# A weboldalon használt betűtípusok

Mindkét betűcsalád **SIL Open Font License 1.1** alatt áll, ami
kifejezetten megengedi a saját kiszolgálóról való használatot.

| Betűcsalád | Készítő | Licenc |
|---|---|---|
| **Archivo** | Omnibus-Type | SIL Open Font License 1.1 |
| **Public Sans** | U.S. Web Design System | SIL Open Font License 1.1 |

A licenc teljes szövege: https://scripts.sil.org/OFL

## Miért vannak itt, és nem a Google CDN-jéről töltjük be őket?

Mert a `fonts.googleapis.com` hívás elküldené a látogató IP-címét a
Google-nek, még mielőtt az bármit elfogadhatna vagy elolvashatna. Így az
oldal betöltése **egyetlen adatot sem küld harmadik félnek**.

## Amit tartunk

Csak a `latin` és `latin-ext` részhalmaz (a magyar **ő** és **ű** a
`latin-ext`-ben van); a vietnami részhalmazt elhagytuk.

Részhalmazonként **egy** fájl: a Google *variable* fontot szolgál ki, a
három betűvastagsághoz bájtra ugyanazt a fájlt küldi — ezt megmértük.
