# De Grote Clichéverwijderaar

> **Schrap de clichés, niet de schrijver.**

De Grote Clichéverwijderaar haalt versleten formuleringen, lege beeldspraak,
voorspelbare gedachten en automatische schrijfpatronen uit Nederlandse teksten.
Dat kunnen menselijke stopzinnen zijn, maar ook typische AI-clichés.

De skill legt geen persoonlijke stijl op. Feiten, betekenis, nuance en de eigen
stem van de schrijver blijven leidend.

## Bestanden

- `SKILL.md`: de volledige instructie voor een AI-assistent;
- `voorbeelden/`: voorbeelden van de drie redactieniveaus;
- `LICENSE`: MIT-licentie.

## Wat de skill aanpakt

- versleten uitdrukkingen zoals `een stip op de horizon`;
- algemene openingen zoals `In een wereld waarin ...`;
- vage taal zoals `de kracht van` en `een waardevolle bijdrage`;
- overdreven woorden zoals `cruciaal`, `baanbrekend` en `transformerend`;
- denkclichés zoals `Verandering biedt ook kansen`;
- automatische contrasten zoals `niet alleen X, maar ook Y`;
- keurige drietallen en alinea's met steeds dezelfde bouw;
- overbodige tussenkoppen, samenvattingen en verbindingswoorden;
- herhaling, overuitleg en passages zonder nieuwe inhoud;
- onbewezen verwijzingen naar onderzoek of experts;
- geforceerde beeldspraak en sloganachtige slotzinnen.

Een cliché is niet simpelweg een veelgebruikte uitdrukking. De skill verandert
een formulering alleen wanneer die weinig betekenis draagt, een concrete
gedachte vervangt of onbedoeld voorspelbaar wordt. Een goede zin blijft staan.

Citaten, spreektaal, humor, personagestemmen en bewuste genreconventies worden
niet automatisch gladgestreken.

## Wat de skill niet doet

- een nieuwe schrijfstijl opleggen;
- persoonlijke anekdotes of meningen verzinnen;
- opzettelijke fouten toevoegen om menselijkheid te simuleren;
- plagiaat of auteurschap verhullen;
- beloven dat een tekst een AI-detector omzeilt.

AI-detectors zijn geen betrouwbare maatstaf voor auteurschap. Deze skill
redigeert tekst; hij bewijst niet wie of wat de tekst heeft geschreven.

## Gebruik

Plaats de map `de-grote-clicheverwijderaar` in de skillsmap van een omgeving die
`SKILL.md` ondersteunt. Geef daarna bijvoorbeeld de opdracht:

```text
Gebruik De Grote Clichéverwijderaar voor deze tekst. Intensiteit: standaard.

[tekst]
```

Andere mogelijke opdrachten:

```text
Pas De Grote Clichéverwijderaar licht toe. Verander alleen de opvallendste clichés.
```

```text
Redigeer deze tekst stevig met De Grote Clichéverwijderaar, maar verander geen
feiten, citaten of vaktermen.
```

## Twee keuzes

### 1. Intensiteit

Bij de start kies je hoeveel er mag veranderen:

1. **Licht opschonen:** alleen duidelijke clichés, opgeblazen woorden en kleine
   herhalingen. Structuur en lengte blijven grotendeels staan.
2. **Stevig redigeren:** ook overbodige uitleg, dubbele gedachten en opgeblazen
   passages worden geschrapt. De tekst wordt merkbaar korter.
3. **Terugbrengen tot de kern:** alles zonder nieuwe informatie, betekenis,
   sfeer of ritme verdwijnt. Alinea's en structuur mogen veranderen.

Niveau 2 is de standaard als je niets specificeert.

### 2. Samenwerking

Daarna kies je hoe de redactie wordt uitgevoerd:

1. **Direct:** je krijgt meteen de volledig aangepaste tekst.
2. **Samen:** je beoordeelt steeds één voorstel met `j` of `n`.

In de samenwerkmodus toont de skill achtereenvolgens het origineel, het voorstel
en een korte reden. `j` past alleen die ene wijziging toe. `n` behoudt alleen die
ene oorspronkelijke passage. Daarna volgt automatisch het volgende voorstel.

Er wordt in deze modus niets stilzwijgend veranderd. Na het laatste voorstel
volgen de volledige definitieve tekst en het aantal geaccepteerde en afgewezen
wijzigingen.

Voorbeeld:

```text
Gebruik De Grote Clichéverwijderaar voor deze tekst.
Intensiteit: 3. Terugbrengen tot de kern.
Samenwerking: samen.

[tekst]
```

## Haal de lucht eruit, niet de adem

De skill controleert of iedere passage iets toevoegt: een feit, observatie,
voorbeeld, stap in de redenering, noodzakelijke nuance of doelbewuste sfeer.
Zinnen die alleen hetzelfde punt uitrekken worden geschrapt of samengevoegd.

Er geldt geen vast verkortingspercentage. Een verhaal mag uitwaaieren wanneer
dat sfeer, timing, spanning, karakter of vertelstem oplevert.

## Goede test

Test de skill op vijf teksten:

1. een duidelijk opgeblazen AI-tekst;
2. een menselijke tekst vol ingesleten uitdrukkingen;
3. een goede menselijke tekst;
4. een technische tekst met noodzakelijke vaktaal;
5. een dialoog of citaat waarin clichés bewust worden gebruikt.

De eerste twee teksten moeten duidelijk verbeteren. De andere teksten moeten
grotendeels ongemoeid blijven. Dat is een belangrijker kwaliteitscriterium dan
zo veel mogelijk veranderingen aanbrengen.

## Bijdragen

Nieuwe Nederlandse clichés en goede voor-en-na-voorbeelden zijn welkom. Dat
geldt ook voor clichés die vaak in AI-tekst voorkomen. Voeg alleen patronen toe
die regelmatig voorkomen. Maak van de skill geen lijst met woorden die onder
alle omstandigheden verboden zijn.
