---
---
Laddningstid
=========================

I den här rapporten har Bashar Altaleb, Muhammed Kheer Abu Khalaf och Idrees Safi valt tre olika webbplatser inom möbelbranschen. Vi tittade närmare på deras laddningstider, storlek på minnet och även rangordna sidorn genom att kolla på olika värden genom devTools och PageSpeed Insights.

##Urval##

Innan vi påbörjade uppgiften valde vi mellan tre olika webbsidor som vi vill använda oss av. Vi kollade lite på olika webbsidor inom olika branscher och tillsut valde vi en specifik bransch som är möbelbranschen.

Bashar valde att analysera BoConcept, Muhammed valde Hooker och Idrees valde Bolia.

##Metod##

Efter valen gjordes över vem som skulle analysera vad så påbörjades analysen av webbplatserna. Varje individ analyserade kritiskt webbplatserna och diskuterade därefter hur webbplatserna kan bli bättre.

För att klara av uppgiften så hade vi stor användning av Firefox DevTools, Google PageSpeed Insights och Movavi ScreenShot. Genom dessa två verktygen fick vi alla våra värden som vi har nämnt senare i rapporten.

##Resultat##

###BoConcept###

####Skärmbild från BoConcepts hemsida####

[FIGURE src=image/boconcept.jpg?w=450&q=90 class="center report" caption="BoConcept furnture home page."]

####Resultatet dokumenterat i en tabell####

<br>
<table>
<thead>
<tr>
  <th>Sida</th>
  <th align="center">Laddtid S (genomsnitt)</th>
  <th align="center">Mobile poäng</th>
  <th align="center">Desktop poäng</th>
  <th align="center">Begäran (requests)</th>
  <th align="center">Storlek MB</th>

</tr>
</thead>
<tbody>
<tr>
  <td><a href="https://www.boconcept.com/sv-se/">Förstasidan</a></td>
  <td align="center">5,81s</td>
  <td align="center">43</td>
  <td align="center">89</td>
  <td align="center">93</td>
  <td align="center">3.96</td>
</tr>
<tr>
  <td><a href="https://www.boconcept.com/sv-se/rooms">Vardagsrum</a></td>
  <td align="center">5.72s</td>
  <td align="center">49</td>
  <td align="center">84</td>
  <td align="center">99</td>
  <td align="center">3.81</td>
</tr>
<tr>
  <td><a href="https://www.boconcept.com/sv-se/shop/foervaring/sideboard">Sideboards</a></td>
  <td align="center">6.03s</td>
  <td align="center">54</td>
  <td align="center">88</td>
  <td align="center">96</td>
  <td align="center">4.02</td>
</tr>
</tbody>
</table>

####Förbättringar####

Förbättringar BoConcept behöver göra på förstasidan för stora skärmar är att skjuta upp inläsningen av bilder som inte dyker upp direkt på skärmen. använda bilder med rätt storlek i modernare bildformat. På andra sidan (vardagsrum) behöver de använda modernare bildformat och ta bort resurser som blockerar renderingen. Den tredje sidan (sideboards) har en en klar seg svarstid från server hållet.

BoConcepts mobilampassade sidor behöver gå under en allvarlig process av förbättringar. Detta eftersom man ser från tabellen att betygsättningen ligger under 50%. De viktigaste aspekterna som leder till drastisk förbättring kan vara att skjuta upp inläsningen av bilder som inte visas på skärmen och skicka bilder i modernare bildformat.


sammanfattningsvis så kan man konstatera från tabellen ovan att BoConcepts laddningstid på datorer är hyfsat bra, men kan bli ännu bättre. Gällande laddningstiden på mobila enheter så behöver webbplatsen i allmänhet mycket jobb för att göra den närma 100%. När det kommer till laddningstid gentemot antalet förfrågningar och den totala storleken på de förfrågningarna så är det logiskt eller närmare sagt rimiligt. Genomsnittet på laddningstiden är nästan 5.8 sekunder och det är ganska långt, men personligen är det okay för mig som användare. Detta eftersom webbsidan i alla de angivna sidor innehåller många bilder och de är oundvikliga när det kommer till marknadsföring av möbler.


##Hooker##

####Skärmbild från Hookers hemsida####

[FIGURE src=image/Hooker.jpg?w=450&q=90 class="center report" caption="Hooker furnture home page."]

####Resultatet dokumenterat i en tabell####


<table>
<thead>
<tr>
    <th>Sida</th>
    <th align="center">Laddtid</th>
    <th align="center">Mobile poäng</th>
    <th align="center">Desktop poäng</th>
    <th align="center">Begäran(requests)</th>
    <th align="center">Storlek MB</th>
</tr>
</thead>
<tbody>
<tr>
    <td><a href="https://www.hookerfurniture.com/">Förstasidan</a></td>
    <td align="center">7.33s</td>
    <td align="center">20</td>
    <td align="center">39</td>
    <td align="center">170</td>
    <td align="center">5,9</td>
</tr>
<tr>
    <td><a href="https://www.hookerfurniture.com/livingroom.inc">Vardagsrum</a></td>
    <td align="center">6,85s</td>
    <td align="center">23</td>
    <td align="center">42</td>
    <td align="center">135</td>
    <td align="center">7.1</td>
</tr>
<tr>
    <td><a href="https://www.hookerfurniture.com/dining-room/sideboard-cabinets/room-type.aspx#top">Sideboards</a></td>
    <td align="center">6.40s</td>
    <td align="center">19</td>
    <td align="center">42</td>
    <td align="center">131</td>
    <td align="center">5.9</td>
</tr>
</tbody>
</table>



####Förbättringar####

Den första sidan (furniture)  av hooker ligger på 20% enligt PageSpeed Insights på mobil och 39% på dator.
Den andra sidan (livingroom) av hooker ligger på 23% enligt PageSpeed Insights på mobil och 44% på dator.
Den tredje sidan (diningroom) av hooker ligger på 19% enligt PageSpeed Insights på mobil och 42% på dator.

Dessa tre sidor på dator har samma problem och man kan förbättra de på samma sätt t.ex när man nimifiera java script , att man skicka bilder i modernare bildformat och koda bilder effektiva . Dessa sakerna man kan använda dem för att förbättra sidan och minifiera ladningstiden.

Det finns små extra saker som kan förbattra sidorna på mobilen som att skjuta upp inläsningen av bilder som inte visas på skärman, använda bilder med mindre storlek , ta bort resurser som blockerar renderingen och ta bort oanvänd css.

Sidorna har problem med laddningstiden, det ökar hela tiden och det är på grund av requests.

##Bolia##

####Skärmbild från Bolias hemsida####

[FIGURE src=image/bolia.jpg?w=450&q=90 class="center report" caption="Bolia furnture home page."]

####Resultatet dokumenterat i en tabell####

<table>
<thead>
<tr>
    <th>Sida</th>
    <th align="center">Laddtid</th>
    <th align="center">Mobile poäng</th>
    <th align="center">Desktop poäng</th>
    <th align="center">Begäran(requests)</th>
    <th align="center">Storlek MB</th>
</tr>
</thead>
<tbody>
<tr>
    <td><a href="https://www.bolia.com/sv-se/">Förstasidan</a></td>
    <td align="center">4.47s</td>
    <td align="center">29</td>
    <td align="center">67</td>
    <td align="center">126</td>
    <td align="center">11.72</td>
</tr>
<tr>
    <td><a href="https://www.bolia.com/sv-se/mobler/vardagsrummet/">Vardagsrum</a></td>
    <td align="center">4.61s</td>
    <td align="center">32</td>
    <td align="center">70</td>
    <td align="center">135</td>
    <td align="center">11.74</td>
</tr>
<tr>
    <td><a href="https://www.bolia.com/sv-se/mobler/forvaring/mediamobler/">Sideboards</a></td>
    <td align="center">3.36s</td>
    <td align="center">37</td>
    <td align="center">78</td>
    <td align="center">110</td>
    <td align="center">6.11</td>
</tr>
</tbody>
</table>


####Förbättringar####
Precis när man öppnar hemsidan så hamnar man på deras startsida vilken fick 67/100 på dator enligt
PageSpeed Insights och 29/100 på mobila enheter. Första sidan hade 126 antal requests och storleken hamnade på 11.72 MB. Laddningstiden som jag anteknade låg på 4.47 sekunder.

Nästa sida som granskades var Vardagsrum där sidan fick 70/100 enligt PageSpeed Insights och 32/100
på mobila enheter. Vardagsrummet hade 135 antal requests och storleken hamnade på 11.74 MB. Laddningstiden för denna sida hamnade på 4.61 sekunder.

Sista sida som granskades genom PageSpeed Insights var Sideboards där sidan fick 78/100 på dator och
37/100 på mobila enheter. Antalet requests som jag antecknade här hamnade på 110 och storleken blev
precis 6.11 MB. Laddningstiden för denna sida för 3.36 sekunder.


##Analys##


Efter att vi alla tre samlade vår data och även analyserade PageSpeed Insight där kunde man tydligt läsa att att förbättraringar som var listade var saker som alla tre sidor hade gemensamt. Något som kan förbättra laddningstiden och dra ner på anatal requesten är att skjuta upp inläsningen av bilder som inte dyker upp direkt på skärmen. Något annat man bör tänka på är att använda bilder med rätt storlek och även mordernare bildformat.

Sidorn har ganska seg svarstid från servern och det beror på resurser som blockerar renderingen. Betygen för alla mobilanpassade sidor ligger på under 50 av 100 och det är tecken på att sidorna behöver allvarliga förbättringar. Precis som nämnt ovan för att göra sidorna ännu snabbare och dra ner på laddningstiden så måste man skjuta upp inläsningen av bilder som inte visas på skärmen och att även skicka bilder i bättre format eller mordernare format med andra ord.


Rangordning i laddningstid:

1. Bolia.
2. BoConcept.
3. Hooker furniture.

Rangordning enligt PageSpeed Desktop/Mobile:

1. BoConcept.
2. Bolia.
3. Hooker furniture.


Vi kom fram till att en laddningstid som vore perfekt är som max 3 sekunder och en långsam sida bör absolut inte ta mer än 5 sekunder. För att då tycker många besökare att sidan tar lång tid och dem  tappar intresse och går vidare till någon annan sida. Vi tycker att webbsidor som vi har valt har långsamma laddningstider för att sidor innehåller väldigt många bilder speciellt Hooker furniture och Bolia. Det är en av största faktorna som gör att det tar tid när sidan laddas. Smartaste lösningen som vi tycker är att skjuta upp inläsningen av bilder som inte dyker upp direkt på skärmen och även använda rätt bildstorlek/format.




##Referenser##

[1] [BoConcept](https://www.boconcept.com/sv-se/)

[2] [Hooker](https://www.hookerfurniture.com/)

[3] [Bolia](https://www.bolia.com/en/)

[4] [Movavi ScreenShot](https://img.movavi.com/online-help/screenrecorder/9/taking_screenshots.htm#)

[5] [PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/)

[6] [Firefox DevTools](http://firefox-dev.tools/)

[7] [Google sheets](https://docs.google.com/spreadsheets/d/1iu2KR-ZcsmCoZta3LCCuN4RYeXPY3PF_mEY3aT0nz64/edit?usp=sharing)



##Övrigt##

Den här rapporten är skriven av Bashar Altaleb, Muhammed Kheer Abu Khalaf och Idrees Safi med ett gott sammarbete.
