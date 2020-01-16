Laddningstid Projekt
=========================

I den här rapporten har Bashar Altaleb, Muhammed Kheer Abu Khalaf och Idrees Safi valt tre olika webbplatser inom försäkringsbolag. Vi tittade närmare på deras laddningstider, storlek på minnet och även rangordna sidorn genom att kolla på olika värden genom devTools och PageSpeed Insights.

##Urval##

Innan vi påbörjade uppgiften valde vi mellan tre olika webbsidor som vi vill använda oss av. Vi kollade lite på olika webbsidor inom olika branscher och tillsut valde vi en specifik bransch som är försäkringsbolag.

Bashar valde att analysera Folksam, Muhammed valde if och Idrees valde Trygg-Hansa.

##Metod##

Efter valen gjordes över vem som skulle analysera vad så påbörjades analysen av webbplatserna. Varje individ analyserade kritiskt webbplatserna och diskuterade därefter hur webbplatserna kan bli bättre.

För att klara av uppgiften så hade vi stor användning av Firefox DevTools, Google PageSpeed Insights och Movavi ScreenShot. Genom dessa två verktygen fick vi alla våra värden som vi har nämnt senare i rapporten.

##Resultat##
###Trygg-hansa###
####Skärmbild på Trygg-Hansa hemsida####
[FIGURE src=image/trygg-hansa.jpg class="center report" caption="Trygg-Hansa home page."]

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
  <td><a href="https://www.trygghansa.se/">Hem</a></td>
  <td align="center">2.83s</td>
  <td align="center">20</td>
  <td align="center">83</td>
  <td align="center">67</td>
  <td align="center">1.88</td>
</tr>
<tr>
  <td><a href="https://www.trygghansa.se/forsakringar/gravidforsakring">GravidFörsäkring</a></td>
  <td align="center">6.68s</td>
  <td align="center">36</td>
  <td align="center">85</td>
  <td align="center">99</td>
  <td align="center">1.98</td>
</tr>
<tr>
  <td><a href="https://www.trygghansa.se/tryggafirman">Tryggafirman</a></td>
  <td align="center">6.61s</td>
  <td align="center">33</td>
  <td align="center">89</td>
  <td align="center">79</td>
  <td align="center">1.80</td>
</tr>
</tbody>
</table>

Precis när man öppnar hemsidan så hamnar man på deras startsida vilken fick 83/100 på dator enligt
PageSpeed Insights och 20/100 på mobila enheter. Första sidan hade 67 antal requests och storleken hamnade på 1.88 MB. Laddningstiden som jag anteknade låg på 2.46 sekunder.

Nästa sida som granskades var GravidFörsäkring där sidan fick 85/100 enligt PageSpeed Insights och 36/100
på mobila enheter. Vardagsrummet hade 99 antal requests och storleken hamnade på 1.98 MB. Laddningstiden för denna sida hamnade på 6.68 sekunder.

Sista sida som granskades genom PageSpeed Insights var Tryggafirman där sidan fick 89/100 på dator och
33/100 på mobila enheter. Antalet requests som jag antecknade här hamnade på 79 och storleken blev
precis 6.11 MB. Laddningstiden för denna sida för 6.61 sekunder.


###IF FÖRSÄKNING###
####Skärmbild på Trygg-Hansa hemsida####
[FIGURE src=image/if.jpg class="center report" caption="If home page."]
####Resultatet dokumenterat i en tabell####

<table>
<thead>
<tr>
    <th>Sida</th>
    <th align="center">Laddtid</th>
    <th align="center">Mobile poäng</th>
    <th align="center">Desktop poäng</th>
    <th align="center">Begäran(requests)</th>
    <th align="center">Storlek kB</th>
</tr>
</thead>
<tbody>
<tr>
    <td><a href="https://www.if.se/privat/forsakringar">Försäkringar</a></td>
    <td align="center">3.62s</td>
    <td align="center">43</td>
    <td align="center">86</td>
    <td align="center">75</td>
    <td align="center">2,45MB</td>
</tr>
<tr>
    <td><a href="https://www.if.se/privat/vid-skada">Skador</a></td>
    <td align="center">2.79s</td>
    <td align="center">56</td>
    <td align="center">88</td>
    <td align="center">74</td>
    <td align="center">2,43MB</td>
</tr>
<tr>
    <td><a href="https://www.if.se/privat/kundservice">Kundservice</a></td>
    <td align="center">2.03s</td>
    <td align="center">69</td>
    <td align="center">93</td>
    <td align="center">58</td>
    <td align="center">2,20MB</td>
</tr>
</tbody>
</table>


####Förbättringar####

Den första sidan (Försäkringar)  av IF.se ligger på 43% enligt PageSpeed Insights på mobil och 86% på dator.
Den andra sidan (Skador) av IF.se ligger på 56% enligt PageSpeed Insights på mobil och 88% på dator.
Den tredje sidan (Kundservice) av hooker ligger på 58% enligt PageSpeed Insights på mobil och 93% på dator.

Dessa tre sidor på dator har en bra ladningstid och requstes är inte mycket så det tar bara några secunder föra att ladasidan men man kan förbettra det för att bli bättre och bättre.men ladningstid med mobilen är ok men inte så bra så man man förbättra den.

det finns små saker man kan göra det förbättrar första sidan med dator och mobilen , om man ta bort resurser som blockerar renderingen det ska ge mer poiner på båda mobilen och datorer. Om man bort oanvänd css och skjut upp inläsningen av bilder som inte visas det förbettra pointer på mobiler också.    

det finns små saker man kan göra det förbättrar andra sidan om man ta bort resurser som blockerar renderingen sen pointer blir mer på mobilen och dator och om man ta bort oanvänd css det göra poiter bättre.

den tredje sidan man kan färbettra pointer om man ta bort resurser som blockerar renderingen kan man också ta bort oanvänd css och  skjut upp inläsningen av bilder som inte visas på sidan för att ha mer pointer


###Folksam###
####Skärmbild på Folksam hemsida####
[FIGURE src=image/folksam.jpg class="center report" caption="Folksams home page."]
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
  <th align="center">Storlek KB</th>

</tr>
</thead>
<tbody>
<tr>
  <td><a href="https://www.folksam.se/">Förstasidan</a></td>
  <td align="center">2,26s</td>
  <td align="center">36</td>
  <td align="center">91</td>
  <td align="center">21</td>
  <td align="center">167,86</td>
</tr>
<tr>
  <td><a href="https://www.folksam.se/forsakringar?icmp=dl_forsakringar">Försäkringar</a></td>
  <td align="center">1.99s</td>
  <td align="center">36</td>
  <td align="center">94</td>
  <td align="center">20</td>
  <td align="center">75,83</td>
</tr>
<tr>
  <td><a href="https://www.folksam.se/kundservice?icmp=dl_kundservice">Kundservice</a></td>
  <td align="center">10,19s</td>
  <td align="center">30</td>
  <td align="center">82</td>
  <td align="center">26</td>
  <td align="center">282,90</td>
</tr>
</tbody>
</table>

Folksam behöver göra på första sidan för datorer är att se till att all text förblir synlig medan webbteckensnitten  läses in, ta bort resurser som blockerar renderingen, undvika ett onödigt stort DOM-träd samt skicka statiska tillgångar med en effektiv chachelagringspolicy. På andra sidan (Försäkringar) behvöver Folksam se till att all text förblir synlig medan webbteckensnitten  läses in och skicka statiska tillgångar med en effektiv chachelagringspolicy. Den tredje sidan (Kundservice) har en en klar seg svarstid och sämsta rangnignen mellan webbplatsens tre sidor. Den sista sidan har samma problem som de första två sidorna har fast med större påverkan av dem.

Folksams mobilampassade sidor behöver gå under en allvarlig process av förbättringar. Detta eftersom man ser från tabellen att betygsättningen ligger under 40%. De viktigaste aspekterna som leder till drastisk förbättring kan vara att ta bort oanvänd CSS, läsa in viktiga resurser i förväg, ta bort resurser som blockerar renderingen, se till att all text förblir synlig medan webbteckensnitten läses in och sist minska påverkan från tredjepartskod.


##Analys##


Efter att vi alla tre samlade vår data och även analyserade PageSpeed Insight där kunde man tydligt läsa att att förbättraringar som var listade var saker som alla tre sidor hade gemensamt. Något som kan förbättra laddningstiden och dra ner på anatal requesten är att skjuta upp inläsningen av bilder som inte dyker upp direkt på skärmen. Något annat man bör tänka på är att använda bilder med rätt storlek och även mordernare bildformat.

Sammanfattningsvis så kan man konstatera från tabellen ovan att laddningstid på datorer är riktigt bra, men kan bli ännu bättre. Gällande laddningstiden på mobila enheter så behöver webbplatsen i allmänhet mycket jobb för att göra den närma 100%.

När det kommer till laddningstid gentemot antalet förfrågningar och den totala storleken på de förfrågningarna så är det logiskt eller närmare sagt rimiligt. Genomsnittet på laddningstiden är nästan 4.8 sekunder och det är ganska långt. Detta eftersom webbsidan i alla de angivna sidor innehåller många bilder och de är oundvikliga när det kommer till illustration av försäkringar.




##Referenser##

[1] [Folksam](https://www.folksam.se/)

[2] [Trygg-hansa](https://www.trygghansa.se/)

[3] [If](https://www.if.se/privat)

[4] [Movavi ScreenShot](https://img.movavi.com/online-help/screenrecorder/9/taking_screenshots.htm#)

[5] [PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/)

[6] [Firefox DevTools](http://firefox-dev.tools/)


##Övrigt##

Den här rapporten är skriven av Bashar Altaleb, Muhammed Kheer Abu Khalaf och Idrees Safi med ett gott samarbete.
