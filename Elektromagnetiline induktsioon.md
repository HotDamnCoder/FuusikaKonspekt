# Elektromagnetiline induktsioon

## Elektromagnetism

**Elektromagnetism** käsitleb elektri- ja magnetnähtuste omavahelisi seoseid ja vastastikke muundumisi. Vaatleb laetud osakeste mitteühtlast liikumist.

Enam ei ole võimalik vaadata elektri- ja magnetnähtusi üksteisest lahus.

Elektromagnetismi muudab keeruliseks temas olev **tagasiside.**

**Tagasiside -** nähtus, mille korral ühe füüsikalise suuruse muutumine põhjustab teiste suuruste selliseid muutusi, mis omakorda mõjutavad esimest suurust.

Kui laetud keha vaatleja suhtes liigub, siis muutub keha elektriväli vaatleja asukohas ja vaatleja registreerib magnetvälja. **(Muutuv elektriväli tekitab muutuva magnetväli)**

Kui magnetvälja tekitaja vaatleja suhtes liigub, siis muutub magnetväli vaatleja asukohas ning vaatleja tähendab muutuva elektrivälja olemasolu **(Muutuv magnetväli tekitab muutuva elektrivälja)**

**Elektromagnetilise induktsiooni nähtus** - magnetvälja muutumine tekitab muutuva elektrivälja.

**Elektromagnetväli** - elektri- ja magnetväli koos vaadatuna ja omavahel seotud

**Vahelduvvool** - vool, mille voolutugevus ja pinge perioodiliselt muutub. Sisuliselt elektromagnetvõnkumised.

**Elektromagnetvõnkumised** - elektri- ja magnetvälja vastastikused muundumised

**Elektromagnetlaine** - elektromagnet võnkumiste levimine ruumis

---
## Pööriselektriväli

**Pööriselektriväli** - elektriväli, mille jõujooned on kinnised, kõverad ehk pöörised. See väli ei ole enam potentsiaalne - töö kinnisel kõveral ei ole enam 0

Elektrimootorite ja generaatorite põhiosad:

1. **rootor** - pöörlev osa
2. **staator** - paigalseisev osa

Paneme raami pöörlema tekib muutuv elektriväli (kuna magnetväli muutub raami suhtes), mis omakorda tekitab muutuva magnetvälja. Kokkuvõtteks tekib elekter.

Oluline on see, et juhe lõikaks magnetvälja jõujooni.

Elektrivool tekib tänu **Lorentz’i jõule** - magnetväljas liikuvale laengule mõjuv jõud

Vooluraami liikumine magnetväljas ei saa rääkida enam potentsiaalist (pinge mingi konkreetse punkti suhtes), sest

* me ei saa eelistada ühtegi raami puntki teisele
* töö kinnisel trajektooril ei ole 0

`F_l = q  * v * B * sin(α)`

Selle raami liikumise juures võib rääkida **elektromotoorjõust**.

**Elektromotoorjõud** iseloomustab raami kui terviklikku vooluallikat.

**Elektromotoorjõud** on võrdne tööga, mida teevad kõrvaljõud ühikulise suurusega laengu ühekordsel läbiviimisel vooluringist.

Elektromagnetilise induktsiooni korral on kõrvaljõud need jõud, mis liigutavat juhet magnetväljas.

Elektromotoorjõud on üldiselt maksimaalne pinge, mida vooluallikas on suuteline tekitama.

Induktsiooni elektromotoorjõud on pinge, mis tekib magnetväljas liikuva juhtmelõigu otstele, kui juhtmes puudub vool.

`elektrivool + magnetväli → liikumine` (Ampere jõud)

`magnetväli + liikumine → elektrivool` (Lorentz’i jõud)

Pinge juhtme otstele (või õigemini elektromotoorjõud) leitakse valemiga:

`E_i = v * l * B * sin(α)`

---
## Magnetvoog

**Magnetvoo** tähis on `Φ`.

**Magnetvoog** näitab millisel määral läbivad magnetvälja jõujooned vaadeldavat pinda selle pinna suuruse ja asendi tõtu magnetväljas.

Piltlikult näitab magnetvooga pinda läbivate jõujoonte arvu.  Mõõtühik `Wb` `(veeber).`

Magnetvoog sõltub:

* pinna suurusest
* magnetvälja tugevusest
* pinna asendist magnetvälja jõujoonte suhtes

`Φ = B * S * cos(α) = n * B * S * cos(α)`, kus `n` on keerdude arv

Magnetvoog on maksimaalne, kui pind on risti jõujoontega.

Faraday seadus - induktsiooni elektromootorjõud on võrdeline magnetvooga muutmise kiirusega.

`E_i = -ΔΦ / Δt` Miinus tuleb Lenz’i reeglist.

Kui on palju keerde, siis magnetvoog võetakse summaarsena `ΔΦ = E_i = Δt`

`1 Wb` on selline magnetvoo muutus, mis `1 sekundi` jooksul toimudes tekitab elektromootorjõu `1 V`

---
## Lenz’i reegel

1. induktsioonivoolu suund on selline, et tema magnetväli takistaks muutust, mis voolu põhjustab
2. induktsioonivool toimib alati vastupidiselt seda voolu esile kutsuvale põhjusele;
3. kui välismõju tingib magnetvoo kasvu kontuuris, siis on induktsioonivoolu magnetväli välise magnetvälja suhtes vastassuunaline (takistab kasvu). Kui aga välismõju põhjustab magnetvoo kahanemist, siis on induktsioonivoolu magnetväli välise magnetväljaga samasuunaline (takistab kahanemist).

---
## Endainduktsioon ja punktinduktsioon

**Endainduktsiooniks** nimetatakse nähtust, kust induktsiooni elektromotoorjõu tekkimiseks vajalik magnetvoo muutus on põhjustatud voolu muutmisest juhtmes endas.

Esineb näiteks siis kui vooluahelas on pool ja me üritame vooluahelast katkestada ja katkestamiskohas tekib tugev säde. Pool hakkab voolu muutumisel toimuma vooluallikana, mille elektromotoorjõudu nimetatakse endainduktsiooni elektromotoorjõuks

Endainduktsiooni esinemine on määratud voolu suutlikusega tekitada antud juhtmesüsteemis magnetvoog.

Juhtmesüsteemi vastavad omaduste kirjeldamiseks on kasutusele võetud induktiivsuse mõiste.

**Induktiivsus - juhi induktiivsus** `L` näitab, kui suur endainduktsiooni elektromotoorjõud `E_e` tekib selles juhis voolu ühikulisel muutumisel ajaühiku jooksul. Ühik `1 H`

`L = E_e / Δi / Δt`

`E_e = -L * Δi / Δt`

`E_e = -ΔΦ / Δt`

`ΔΦ = L * Δi`

Juhi induktiivsus näitab, kui suure magnetvoo muutus tekitab selle juhi korral ühikuline voolu muutus.

---
## Magnetvälja energia

Tegelikult on tegemist vooluga poolis tekkiva energiaga.

`W_m = L * I^2 / 2`

---
