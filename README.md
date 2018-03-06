
# SpedeScript ohjelmointikieli

Jo edesmenneen suurmiehen, [Pertti Olavi "Spede" Pasasen](https://en.wikipedia.org/wiki/Spede_Pasanen) ja alitajuisesti [ArnoldC](http://lhartikk.github.io/ArnoldC/):n innoittama ohjelmointikieli.

Toistaiseksi aika raakile koska ei ole a) osaamista b) aikaa c) kiinnostusta viedä tätä teenpäin. Jos itselläsi on viljalti aikaa ja kiinnostusta niin vie ihmeessä eteenpäin. Osaamisella ei niin väliä, ei toki haittaakaan. Forkkaa tai jotain.

Kielen ydinajatus on että se on helppo oppia, koska niin paljon hoituu samoilla keywordeilla - ei tarvitse käyttää aikaa ja niiden muisteluun. SpedeScript sopii erinomaisesti savolaisen koulukunnan mukaisen arkkitehtuurin omaavien kvanttitietokoneiden ohjelmointiin. Esimerkiksi tekoäly- ja lohkoketjutoteutuksiin se on omiaan ja on aito vaihtoehto [Microsoftin Q# -kielelle](https://docs.microsoft.com/en-us/quantum/quantum-qr-intro?view=qsharp-preview).

## SpedeScript Esimerkki

```
#include "spedescriptlib.hpp"

suottaapi x olla_vuan (2)

suattaapi uuno_turhapuro olla_vuan ("Uuno")
suattaapi kauppaneuvos_tuura olla_vuan ("Tuura")

suottaapi olla
  nimittain (x)
    suattaapi_olla_etta (1)
      helvata (uuno_turhapuro)
    suattaapi_olla_etta (2)
      helvata (kauppaneuvos_tuura)
    vuan_suattaapi_olla
      voe_rahma
  eheheh
eheheh
```

## Lisenssi

SpedeScript on vapaasti käytössä [savolaisen softalisenssin (SSL)](https://github.com/janit/spedescript/blob/master/LICENSE) määräämissä puitteissa.

[SpedeScript](https://janit.iki.fi/spedescript/)
