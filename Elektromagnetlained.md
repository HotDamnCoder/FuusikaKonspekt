# Eelmine ptk - [[Elektromagnetiline induktsioon]]
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
* **efektiivväärtus (** `I_ef` , `U_ef` ) (Maksimaal väärtused jagatud ruutjuur kahega)

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

**Induktviitakistus** `R_l`  on takistus, mida tekitab vahelduvoolu ahelasse lülitatud pool. Tekib tänu endainduktsiooninähtusele. Pinge ja voolutugevus eri faasis.

`w = 2pi * f`
`R_l = X_l = w * L`

**Mahutuvustakistus** `R_c` on takistus, mida tekitab vahelduvvoolu ahelasse lülitatud kondensaator. Pinge ja voolutugevus eri faasis.

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

## Elektromagnetlainete omadused
* Peegelduvad metallpindadelt
* Esineb difraktsioon - paindumine tõkete taha
* Esineb interferents - lainete liitumine
* Murduvad erinevates keskkondades.
* Neelduvad
* Tekivad ja kaovad kindlate energia portsjonite e kvantide kaupa `E = h * f`

## Elektromagnetlainete skaala
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

### Madalsageduselained
`f = 0 - 10^4 Hz`
`λ = 10^4 m` ja suurem
* Sisuliselt vahelduvvool
* Tekitab vahelduvvoolu generaator
* Levivad elektrijuhtides
* Vaakumis või õhus levik väike
* Põhimõtteliselt elektrienergialevik

### Raadiolained
`f = 10^5 - 10^12 Hz`
`λ = 10^4 - 10^-4 m`
* Elektromagnetilise info edastuse põhivahend
	* kasutatakse raadios, televisoonis, radarites, telefonides
* Tekitab suletud võnkering
* Kiirgab avatud võnkering (antenn)

Raadiolained jagunevad:
1.  milli- ja sentimeetrilaineteks
	* satelliidid, televisioon ja radarid
2.  detsimeetrilaineteks
	*  televisioon
3.  meeterlaineteks
	*  raadio

Meeterlained jagunevad veel omakorda:
1. (1 kuni 10m) Ultralühilaine (FM)
	* ERR töötab selle sageduse peal
	* FM - sagedus modulatsioon
	* Antennid kõrged, saatjad väikse võimsusega
2. Lühilaine (10 kuni 100m)
	* kasutavad peamiselt raadioamatöörid
3. Kesklaine (AM) (100 kuni 1000m)
	* Eestis pole selliseid raadiojaame
	* Antenn madal, saatja võimsus suurem
	* Laineraadius suurem
4. Pikklaine (1km või üle)
	* saatjad suure võimsusega, levib hästi kaugele
		* allveelaevad
	* Venemaal kaks saatjad

### Optilinelaine
`f = 10^12 - 10^17 Hz`
`λ = 10^-4 - 10^-8 m`
1. Infravalgus e. soojuskiirgus
	* tekib aatomite võnkumisel või pöörlemisel
2. Nähtavvalgus
	* tekitab aatomite väliskihtide elektronid
3. Ultravalgus ehk UV
	* tekitab aatomite väliskihtide elektronid
	* tekitab päevitust

### Röntgenkiirgus
`f = 10^16 - 10^19 Hz`
`λ = 10^-8 - 10^-11 m`

Tekitamine:
1. elektronide järsul pidurdamisel
2. aatomite sisekihtide elektronide

Kasutatakse meditsiinis, tungib läbi inimkeha, üldiselt paha

### Gammakiirgus
`f = 10^19 - 10^23 Hz`
`λ = 10^-10 - 10^-14 m`

* Tekib aatomituumades radioaktiivsel lagunemisel
* Suur läbi tungimis võime
* VÄGA PAHA (v.a Ida-Virumaal)

### Üldine jutt
Mida väiksem tekitaja, seda väiksem lainepikkus, seda suurem sagedus.
Lained levivad üldiselt kindalate portsioonide ehk kvantide kaupa
Mida suurem sagedus, seda väiksem lainepikkus, seda suurem energia, seda rohkem pahandust tekitab
Mida väiksem sagedus, seda rohkem avalduvad laine omadused (nt: interferents ja diffraktsioon)



