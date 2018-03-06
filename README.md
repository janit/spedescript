
# SpedeScript ohjelmointikieli

Jo edesmenneen suurmiehen, [Pertti Olavi "Spede" Pasasen](https://en.wikipedia.org/wiki/Spede_Pasanen) ja alitajuisesti [ArnoldC](http://lhartikk.github.io/ArnoldC/):n innoittama ohjelmointikieli.

Toistaiseksi aika raakile koska ei ole a) osaamista b) aikaa c) kiinnostusta viedä tätä teenpäin. Jos itselläsi on viljalti aikaa ja kiinnostusta niin vie ihmeessä eteenpäin. Forkkaa tai jotain.

Kielen ydinajatus on että se on helppo oppia, koska niin paljon hoituu samoilla keywordeilla - ei tarvitse käyttää aikaa ja niiden muisteluun.

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

[SpedeScript](https://janit.iki.fi/spedescript/)
