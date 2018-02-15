# TKT20007-Ohjelmistotuotantoprojekti [&#128279;](https://courses.helsinki.fi/fi/tkt20007)

### Projektin tavoite

- Ryhmätyötaitojen harjoittelu.
- Ohjelmiston tuotantomenetelmien käytännön harjoittelu.

## Projektin kulku

- Noudatetaan Scrum-henkistä prosessia.
- Kahden viikon välein asiakastapaaminen (Sprint Review), jonka jälkeen Sprint Planning ja Sprint Retrospective.
- Mahdollisuuksien mukaan päivän aluksi Daily Scrum.
- Ensimmäinen viikko ns. nollasprintti, josta lisää alempana.
- Tarkastellaan jatkuvasti prosessin toimivuutta Sprint Retrospectivessä. 
  - Transparency, Inspect & Adapt! 
- Ensimmäisessä asiakastapaamisessa pyritään määrittelemään [Minimum Viable Product](https://en.wikipedia.org/wiki/Minimum_viable_product), koska tarkoituksena on saada ohjelma tuotantoon mahdollisimman nopeasti.

### Nollasprintti

Perustakaa **heti** jonkinlainen yhteinen TODO-lista. Kirjatkaa sinne nollasprintin tehtävät. Siellä tulisi olla ainakin nämä:
- [ ] Slack-ryhmä pystyyn
  - Ohjaajalle kutsu
- [ ] Product backlogin laatiminen
- [ ] Sprint Task Board / Sprint backlog (fyysinen tai sähköinen)
- [ ] Tuntikirjanpito, josta näkee jokaiseen viikkoon käytetyt tunnit opiskelijoittain
- [ ] Luokaa GitHub-organisaatio ja repository
  - "Päärepon" readme:ssä oltava linkit ryhmän backlogeihin, sovellukseen, yms
- [ ] Sopikaa käytettävät teknologiat
  - Huom! Asiakkailla voi olla mielipide käytettävistä teknologioista tai koodauskäytännöistä.
- [ ] CI- ja staging-ympäristö mahdollisimman nopeasti pystyyn.
- [ ] Branching-käytännöistä sopiminen
  - Hyvä käytäntö on pitää master-haarassa vain tuotantokelpoista (deployable) koodia. Näin voidaan aina siirtää koodi staging-palvelimelle (ja myöhemmin tuotantoon.)
- [ ] Koodauskäytännöt
  - Sopikaa Definition of Done
  - Pitää olla sellainen, että DoDin kriteerit täyttävä story voitaisiin viedä sellaisenaan tuotantoon!
  - Huom: DoD:ia voi päivittää tiukemmaksi projektin edetessä
- [ ] Valituilla teknologioilla toteutettu "hello world" / [Walking skeleton](http://wiki.c2.com/?WalkingSkeleton) -sovellus staging-ympäristöön. 
  - _"A Walking Skeleton is a tiny implementation of the system that performs a small end-to-end function"_

## Kurssin vaatimuksia

### Backlogit

- **DEEP** Product Backlog pitää olla DEEP.
- **User storyt** Vaatimukset User Story -muodossa. INVEST on tärkeä!
- **Hyväksymiskriteerit** Storylla pitää olla hyväksymiskriteerit (Acceptance critieria), jos se on Product Backlogissa korkealla (=tulee kohta tehtäväksi). Kriteerit kannattaa käydä läpi koko tiimin ja asiakkaan kanssa, vaikka kaikkia ei tarvitse kirjoittaa asiakkaan läsnäollessa. Lue hyvistä käytännöistä alla.
- **Storyjen seuranta** Seurataan missä sprintissä valmistuneen storyn tekeminen on aloitettu. Tarkoituksena on, että kaikki storyt olisivat valmiita samassa sprintissä kuin ne on aloitettu, mutta metriikoiden optimointi ei saa missään nimessä olla itsetarkoitus — storyn pitää olla aidosti laadukkaasti tehty ja muilta osin valmis ennen kuin se lasketaan tehdyksi.

### Deployment environments
  - **Staging-ympäristö** mahdollisimman tuotannon kaltainen.
  - **Tuotantoon!** Tuotos täytyy saada tuotantoon jo projektin aikana, mielellään mahdollisimman nopeasti.
  - **Demot stagingista** Asiakkaalle demotaan ainoastaan vain ja ainoastaan staging-palvelimelta, ei omalta koneelta.
- **Testaus**
  - Automaatiotestauksen pitää olla riittävän kattava ja hyvin toteutettu
  - Kaikkien yksikkötestien ajaminen on hyvä kestää korkeintaan muutaman minuutin. Korkeamman tason testien, kuten UI-testien ajo saa kestää pidempään, eikä niitä tarvitse ajaa yhtä usein.
  - Erittäin tärkeä konsepti on ns. testipyramidi http://martinfowler.com/bliki/TestPyramid.html. Parin minuutin lukeminen voi säästää kymmeniä tunteja aikaa.
  - Testikoodin laatu tulee mielellän olla yhtä hyvää kuin muunkin koodin.

### Sekalaisia vaatimuksia

- **Tuntikirjapito** Kurssin aikana seurataan tuntimääriä. Työtunneiksi lasketaan myös tapaamiset, esim. tiimin kanssa yhdessä lounastamiset ja itseopiskelu.
- **Kurssi = 200h** Vaatimuksena noin 200 tuntia työtä koko kurssin aikana, mikä on noin 15-16 tuntia viikossa.
- **Tasaisuus** Ehdottomana vaatimuksena työmäärien tasaisuus viikkotasolla, eli tuntimäärän kuuluu olla viikosta toiseen suunnilleen sama. Sairastumiset yms. neuvoteltava poikkeus. Ilmoita reilusti etukäteen jos tiedät, että osallistumisesi viikon töihin estyy jollain tapaa.
- **Kunnioita** kanssaopiskelijoitasi, kyseessä ei ole yksilökurssi. 
  - Käyttäydy samojen standardien mukaan kuin olisit töissä.
  - Sovittuihin yhteisiin tapaamisiin pitää tulla. Myöhästymisistä, esteistä yms. pitää ilmoittaa ajoissa.
- Siiloutumista tulee välttää. Koodikatselmoinnit!
- **Asiakastapaamiset**
  - **Tilavaraukset** Ensimmäisen asiakastapaamisen jälkeen ryhmä on vastuussa asiakastapaamisten järjestämisestä. Huoneiden varaus onnistuu Office 365 -sovellusta käyttämällä.
  - **Agenda** Asiakastapaamisiin kannattaa luoda melko yksityiskohtainen agenda ja se on hyvä lähettää asiakkaalle ennen varsinaista tapaamista.
 
## Arvosteluperusteet
- Asiakkaan arvio (lopussa).
- Koodin yleinen laatu.
- Valmistautuminen asiakastapaamisiin ja toiminta asiakaspalaverissa.
- Sitoutuminen ryhmän kesken sovittuihin käytäntöihin.
- Käytäntöjä voidaan muuttaa vielä jälkeenpäin.
- Ryhmäläisten vertaispalautteet.
- I-periodin ja II-periodin lopussa.

## Vinkkejä
- Töitä kannattaa tehdä mahdollisimman paljon muiden kanssa fyysisesti samassa tilassa.
- Sprintin aikana on hyvä olla tekeillä ainoastaan 2-3 storya kerrallaan. Tällöin storyt valmistuvat varmemmin. Muutama valmis > melkein kaikki kesken.
- Ohjelmiston arkkitehtuuriin kannattaa käyttää paljon huomiota ja jättää sprinttiin aikaa tehdä parannuksia sisäiseen laatuun. Puhdas User Story -hikipaja, jossa keskitytään ainoastaan mahdollisimman nopeaan ominaisuuksien tuottamiseen ei pitkällä tähtäimellä tuota hyviä tuloksia.
- Voi olla hyvä idea hahmotella hyväksymiskriteerit ennen varsinaista asiakastapaamista. Kannattaa kuitenkin jättää hieman pureskeltavaa kriteereihin ennen tapaamista.
- On hyvä käytäntö pitää agenda näkyvillä asiakastapaamisen aikana, jotta keskustelu saadaan pysymään paremmin aiheessa. Käydään kokouskäytäntöjä tarpeen mukaan läpi yhdessä.