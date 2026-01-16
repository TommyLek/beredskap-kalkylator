# Beredskapsersättning Kalkylator

Kalkylator för att beräkna beredskapsersättning enligt **Handelns tjänstemannaavtal** (1 maj 2025 - 30 april 2027).

Verktyget är specifikt anpassat för **Beredskapstjänst II** med ordinarie arbetstid 09:00-18:00.

## Funktioner

### Webbkalkylator (`beredskap-kalkylator.html`)
- Välj vecka med datumväljare
- Klicka på dagar för att markera/avmarkera arbetsdagar
- Automatisk identifiering av svenska helgdagar (inkl. rörliga som påsk, midsommar)
- Beräkning av ersättning per tidsperiod
- Detaljerad fördelning per dag
- Exportera till PDF

### Excel-kalkylator (`Beredskapsersattning_kalkylator.xlsx`)
- Beräkning för normalvecka
- Ändra månadslön i cell B5 för automatisk omräkning
- Detaljerad uppdelning per ersättningsnivå

## Ersättningsnivåer (Beredskapstjänst II)

| Nivå | Period | Divisor |
|------|--------|---------|
| Grundersättning | Vardagar kväll/natt | 1/1400 |
| Fredagskväll/natt | Fre 18:00 - Lör 07:00 | 1/1000 |
| Helgersättning | Lör 07:00 - Sön 24:00 | 1/700 |
| Storhelg | Jul, påsk, midsommar, pingst, nyår | 1/350 |

## Användning

### Webbkalkylator
1. Öppna `beredskap-kalkylator.html` i en webbläsare
2. Välj vecka och ange månadslön
3. Klicka på dagar för att justera arbetsdagar
4. Resultatet beräknas automatiskt

### Excel
1. Öppna `Beredskapsersattning_kalkylator.xlsx`
2. Ändra månadslön i cell B5
3. Ersättningen beräknas automatiskt

## Svenska helgdagar som ingår

**Fasta:**
- Nyårsdagen, Trettondagen, Första maj, Nationaldagen
- Julafton, Juldagen, Annandag jul, Nyårsafton

**Rörliga:**
- Påsk (Skärtorsdag, Långfredag, Påskafton, Påskdagen, Annandag påsk)
- Kristi himmelsfärd
- Pingst (Pingstafton, Pingstdagen)
- Midsommar (Midsommarafton, Midsommardagen)
- Alla helgons dag

## Licens

Fritt att använda.
