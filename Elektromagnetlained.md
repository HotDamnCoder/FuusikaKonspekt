# Elektromagnetlained
## Elektromagnet võnkumised
### Vahelduvvool ja selle kirjeldamine
**Vahelduvvooluks** nimetatakse elektrivoolu, mille korral voolutugevus perioodiliselt muutub.

Reeglina muutub voolusuund.

Vahelduvvoolu iseloomustavad:

* **sagedus (** `f` **)**
* **periood (** `T` **)**
* **hetkväärtus (** `i`**,** `u` )
* **maksimaalsed väärtused (** `I_m`, `U_m` )
* **efektiivväärtus (** `I` , `U` ) (Maksimaal väärtused jagatud ruutjuur kahega)

Tavaliselt on vahelduvvoolu korra tegemist harmoonilise võnkumisega. Tegemist on sundvõnkumisega ehk perioodilise välisejõu mõjul tekitatud võnkumisega.

Vahelduvvoolu võrk koosneb elektrienergia tarvitid, elektrijaamad, ülekandeliinid.

Vahelduvvoolu pistikus peaks olema kolm juhet:

* **faasijuhe**
* **nulljuhe**
* **maandusjuhe**

Vahelduvvool tekitatakse mehaanlise generaatoriga.

#### Kolmefaasiline vool (tööstusvool)
Kujutab endas 3 elektrivooluga juhet ja ühte nulljuhet. Vooluga juhtmetes on voolu faasivahe on 120 kraadi.

Kolmefaasilist voolu kasutatakse suurte võimsuste juures.

#### Takistused vahelduvvoolu ahelas
Vahelduvvoolu ahelas on 3 liiki takistusi:

* **aktiivtakistus**
* **mahtuvustakistus**
* **induktviitakistus**

**Aktiivtakistus** `R` on takistus, mis on olemas ka alalisvoolu korral ja on põhjustatud laengukandjate vastastikmõjust ioonidega.

Pinge ja voolutugevus muutuvad samas faasis.

**Induktviitakistus** `R_l`  on takistus, mida tekitab vahelduvoolu ahelasse lülitatud pool. Tekib tänu endainduktsiooninähtusele. Pinge ja takistus eri faasis.

`R_l = X_l = w * L`

**Mahutuvustakistus** `R_c` on takistus, mida tekitab vahelduvvoolu ahelasse lülitatud kondensaator. Pinge ja takistus eri faasis.

Kondensaatorit võib vaadelda lisa vooluallikana, mis takistab voolu muutumist.

`R_c = X_c = 1 / w * C`

Kui sagedus on vool, siis on takistus lõpmatu suur ehk alalisvool ei läbi kondensaatorit.

**Kogutakistus** `Z` pole takistuste summa, kuna nendes esineb faasi vahe.

`Z = sqrt(R^2 + (R_l - R_c)^2)`

`I_o = U_o / Z`

### Vahelduvvoolu võimsus
Võimsuse järgi võib koduseid seadmeid jaotada 3 rühma:

* Audio, video ja muud seadmed - nende energiatarbe pole väga suur, üldjuhul tarbivad alalisvoolu
* Kasutavad elektrivoolu soojusliku toimet - reeglina ainult aktiivvõimsus
* Seadmed, mis sisaldavad elektrimootorit - `A = A_m + Q`

Alalisvoolu võimsus - `P = U * I`

Vahelduvvoolu võimsus - `P = U * I cos(Φ)` `P_ef = 0.5 * P_m`

`P_m = I_m * U_m` `P_ef = I_ef * U_ef = I_m / sqrt(2) * U_m / sqrt(2)`

`Φ` on faasivahe.

---
## Trafo
**Trafo** on elektromagneetliisel induktsioonil põhineb staatiline energiamuundur, mis võimaldab vahelduvpinget ja vasatavalt vahelduvvoolu konstantne pingel. Koosneb raudsüdamikust ja 2 või enamast poolist.

Trafol on kaks mähist:  **primaar**- ja **sekundaarmähis.**

**Primaarmähis** - kuhu antakse voolu

**Sekundaarmähis** - kust muundatud vool välja tuleb

Primaarmähisesse lastakse vahelduvvool, mis tekitab muutuva magnetvälja, mis kutsub esile muutuva magnetvoo. Magnetvoo muutus indutseerib sekundaarmähises vahelduvvoolu, kui on tarbija.

`n = N_1 / N_2 = U_1 / U_2 = I_2 / I_1`

Kuna võimsused mõlemad mähises peavad olema samad, siis muutub voolutugevus pöördvõrdeliselt pingega.

Kui n = 1, siismidagi ei muutu, aga voolud on eraldatud.

Trafode kasutegur on 95% - 99%.

### Trafode kasutamine
* Elektrienergia ülekanne, et vähendada kadusid
* Voolu tõstmine keevitamiseks
* Vooluahelate sidestamiseks
* Infoseadmetes tööpinge saamiseks

---
## Elektromagnetvõnkumine. Võnkering
Võnkering on induktiivpoolist ja kondensaatorist koosnev elektriahel.

`W_m = (L * I^2) / 2`

`W_e = (C * U^2) / 2`

Võnkeringis tekivad vabavõnked sagedusel, mille juhul pooli induktiivtakistus on võrdne kondensaatori takistusega.

Vabavõnkumine - võnkumine, millele ei mõju väliseid jõudusid

Võnkering saab oma energia kondensaatori laadumisest. Pärast pooli ühendamist kondensaatoriga, hakkavad toimuma vabavõnkumised.

Võnke sageduse leitakse Thomsoni valemiga `f_o = 1 / (2 * pi * sqrt(L * C)`

### Võnkeringi töö
* Laaditakse kondensaator
* Kondensaator hakkab läbi pooli tühjenema
* Poolis tekib endainduktsiooni elektromotoorjõu, mis takistab voolukasv. Kui kondensaatori pinge on 0, siis on voolutugevus maksimaalne.
* Vool hakkab kahanema
* Pooli endainduktsiooni elektromotoorjõud takistab kahanemist.
* Kondensaator on laadunud vastupidiselt.
* Voolusuunud muutub ja tsükkel hakkab uuesti.

---
## Elektromagnetväli ja -lained
Elektromagnetvõnkumine - võnkeringis tekkinud võnkumine.

Elektri- ja magnetväli moodustavad ühtse terviku - elektromagnetvälja.

Nüüdsest ei saa enam neid välju eraldi vaadata.

Elektromagnetväli kujutab endast üksteisest sõltuvat elektri- ja magnetvälja.

Elektromagnetvälja levimist ruumis nimetatakse elektromagnetlaineks.

Elektromagnetlaine levik:

* Elektrivälja muutumine ühes punktis põhjustab kõigepealt muutuva magnetvälja
* Selle magnetvälja muutus kutsub elektromagnetinduktsiooni teel esile elektrivälja muutuse naaberpunktis.
* Muutus magnetväljas tekitab muutuse elektriväljas.

Tavaliselt  saadakse elektromagnetlaine, kui pannakse laeng võnkuma.

Elektromagnetlaine on ristlaine.

`f = v / λ`

Selleks, et elektromagnetlaineid kiirta minnakse üle avatud võnkeringile.

Reaalselt moodustakse avatud võnkering antenni ja maandusega.

Kiirgavate elektromagnetlainete energia kohta kehtib seos:

* `W_eml = const * f^4` Elektromagnetlaine energia sõltub sageduse 4. astmest
* Suurem sagedus → paremini levib
* Suurem sagedus → väiksem lainepikkus

### Elektromagnetlainete omadused
* Peegelduvad metallpindadelt
* Esineb difraktsioon - paindumine tõkete taha
* Esineb interferents - lainete liitumine
* Murduvad erinevates keskkondades.
* Neelduvad
* Tekivad ja kaovad kindlate energia portsjonite e kvantide kaupa `E = h * f`

### Elektromagnetlainete skaala
Sagedus ja lainepikkus on omavahel seotud.

Jaotatakse sageduse põhjal:

* Madalsagedus
* Raadiolained
* Optiline kiirgus
  * infrapuna
  * nähtav valgus
  * ultraviolet
* röntgenkiirgus
* gammakiirgus

---