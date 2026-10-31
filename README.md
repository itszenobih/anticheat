Ce face

Anti-spam: al 3-lea mesaj identic în 10 secunde dă mute 30 de secunde. A doua oară dă mute 10 minute. Dacă nu mai spamează 30 de minute, contorul se resetează. Adminii sunt exceptați și primesc notificare când cineva e mutat.
Detectează: fly pe jos, airbreak, teleport (pe jos și cu mașina), speed hack la vehicule, jetpack, health/armour hack, arme date din cheat, money hack și rapid fire.
Fără sancțiuni automate: nu dă kick, ban sau mute pentru cheat. Doar trimite alerte adminilor, în formatul [AntiCheat] Nume [id] suspect de Fly Hack (detalii) | ping | alerte.
Comandă pentru admini: /acinfo [id] arată câte alerte are un jucător, pe fiecare tip.

Cum evită alertele false

Fiecare detecție are un prag. Fly, de exemplu, cere 6 verificări la rând, iar rapid fire cere 8 semnale într-un interval scurt.
Alertele pentru același jucător și același tip au pauză de 20 de secunde, ca să nu inunde chatul adminilor.
Verificările se opresc câteva secunde după spawn, moarte, schimbare de interior, intrare în mașină, pickup sau orice teleport făcut de tine.
Adminii, jucătorii cu ping peste 500 și NPC-urile nu sunt verificați.

Ce trebuie să știi

Ca să nu primești alerte false, health, armură, bani, arme și poziții trebuie schimbate prin funcțiile obișnuite (SetPlayerHealth, GivePlayerMoney, GivePlayerWeapon, SetPlayerPos etc.). Fișierul le înlocuiește singur, dar dacă modifici banii sau armele prin alt mecanism (de exemplu un plugin), vei primi alerte pentru ele.
Un anticheat scris doar în pawn, fără plugin, nu prinde toate cheat-urile. Cele mai bune rezultate sunt la fly, teleport, airbreak, jetpack, bani, arme și spam.
Dacă primești prea multe alerte false, mărește valorile din acPrag și limitele de viteză din cod.
