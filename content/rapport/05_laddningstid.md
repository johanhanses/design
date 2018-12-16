Analys av tre webbplatsers laddningstid
=======================

I denna rapport så ska jag titta på tre olika webbplatsers laddningstid och hur de laddar sitt innehåll.

Urval
-----------------------

Jag har valt tre webbplatser som alla är kommuners webbsidor.
>    <a href="http://www.leksand.se" target="blank">Leksands kommun.</a>
>
>    <a href="http://www.falun.se" target="blank">Falu kommun.</a>
>
>    <a href="http://www.borlange.se" target="blank">Borlänge kommun</a>

Utvalet gjordes utifrån tre kommuner i mitt län som jag själv har någon anknytning till.

Metod
-----------------------
För att lösa denna uppgift så har jag använt mig av googles <a href="https://developers.google.com/speed/pagespeed/insights/" target="blank">PageSpeed Insights</a> samt devtools verktyget i Firefox developer edition.

Alla mätningar är gjorda den 10/12 -2018.

Alla mätningar med devtools är gjorda tre gånger i följd med webbläsarens cashe tömd vid omladdningen av webbplatserna. Resultaten redovisas nedan men även i detalj i mitt google kalkylark här nedan. 

Länk till mitt <a href="https://docs.google.com/spreadsheets/d/1jLdncJPhk00blhSP1TIC-zRx2SNk8o22RbDGYvRHyMw/edit?usp=sharing" target="blank">kalkylark</a> där all data från mina tester finns att se

Resultat
-----------------------

###leksand.se

[FIGURE src="image/leksand.se.png?w=600" class="center" caption="Leksand kommuns webbplats leksand.se" alt="leksand.se"]

Startsidan: <a href="http://leksand.se/" target="blank">http://leksand.se/</a>  
Startsidans pagespeed-betyg är 18 för mobil och 79 för dator

Första undersidan: <a href="http://leksand.se/Utbildning-och-barnomsorg/" target="blank">http://leksand.se/Utbildning-och-barnomsorg/</a>  
Första undersidans pagespeed-betyg är 31 för mobil och 85 för dator

Andra undersidan: <a href="http://leksand.se/Omsorg-och-hjalp/" target="blank">http://leksand.se/Omsorg-och-hjalp/</a>  
Andra undersidans pagespeed-betyg är 31 för mobil och 85 för dator

För leksand.se så tycker google pagespeed insights att den främsta förbättringsåtgärden är att minska svarstiden från servern, hela 3,27 sekunder verkar kunnas sparas in gällande den punkten. Nästkommande förslag är alla relaterade till sidans bilder och dess format och storlek.

###falun.se

[FIGURE src="image/falun.se.png?w=600" class="center" caption="Falu kommuns webbplats falun.se" alt="falun.se"]

Startsidan: <a href="https://www.falun.se/" target="blank">https://www.falun.se/</a>  
Startsidans pagespeed-betyg är 24 för mobil och 97 för dator

Första undersidan: <a href="https://www.falun.se/utbildning--barnomsorg.html" target="blank">https://www.falun.se/utbildning--barnomsorg.html</a>  
Första undersidans pagespeed-betyg är 33 för mobil och 99 för dator

Andra undersidan: <a href="https://www.falun.se/stod--omsorg.html" target="blank">https://www.falun.se/stod--omsorg.html</a>  
Andra undersidans pagespeed-betyg är 32 för mobil och 99 för dator

För falun.se så tycker google pagespeed insights att den främsta förbättringsåtgärden är att ta bort resurser som blockerar renderingen av sidan, mer ingående så uppmanas man att att infoga nödvändig css-/js-kod direkt på sidan och att skjuta upp inläsningen av javascriptkod och formatmallar som är mindre viktiga. 1,42 sekunder skulle sparas in genom denna åtgärd. Även här så är nästkommande förslag relaterade till sidans bilder och dess format och storlek.

###borlange.se

[FIGURE src="image/borlange.se.png?w=600" class="center" caption="Borlänge kommuns webbplats bolange.se" alt="borlange.se"]

Startsidan: <a href="https://www.borlange.se/" target="blank">https://www.borlange.se/</a>  
Startsidans pagespeed-betyg är 44 för mobil och 98 för dator

Första undersidan: <a href="https://www.borlange.se/barn-och-utbildning/" target="blank">https://www.borlange.se/barn-och-utbildning/</a>  
Första undersidans pagespeed-betyg är 40 för mobil och 97 för dator

Andra undersidan: <a href="https://www.borlange.se/omsorg-och-hjalp/" target="blank">https://www.borlange.se/omsorg-och-hjalp/</a>  
Andra undersidans pagespeed-betyg är 39 för mobil och 97 för dator

För borlange.se så tycker google pagespeed insights att den främsta förbättringsåtgärden är att skicka bilderna i ett modernare bildformat såsom JPEG 2000, JPEG XR och WebP. 2 sekunder skulle kunna sparas in genom denna åtgärd. Att använda bilder med rätt storlek skulle även kunna spara in 1,96 sekunder.


Analys
-----------------------
De olika webbplatsernas bilder, dess storlek, format och hur de kodats verkar vara genomgående något som kan förbättras. Sedan noterade jag själv när jag besökte webbplatserna initialt att leksand.se tog väldigt lång tid på sig att ens börja visa sitt innehåll. Att detta beror på lång svarstid från servern vet jag nu men jag skulle gärna vilja veta mer om hur man förbättrar detta, lägger upp sidan på en annan server?  
Jag blir generellt mest sugen på att lägga mer tid på art direction och att prova alla dessa nya bildformat för att se skillnaden på min egen redovisasida. Men det får bli ett senare experiment.

Sidornas laddningstid kan rangordnas enligt nedan, med bäst betyg enligt google pagespeed insights först:  
1. borlange.se  
2. falun.se  
3. leksand.se  

Även fast det skiljer väldigt lite mellan borlange.se och falun.se så upplevs borlange.se tydligt som snabbare vilket sannolik har att göra med att falun.se har ett bildspel/film "above the fold" vilken tar lite längre tid än övrigt innehåll på sidan att ladda.
Dock så tar borlange.se längre tid på sig att ladda hela sitt innehåll enligt firefox devtools. Men sidan laddar liksom innehållet på ett sätt så att de delar som kommer senare inte upplevs som nödvändiga för att börja tillskansa sig den information som sidan förmedlar och i fallet med kommuners webbplatser så känns detta relevant och gör borlange.se till vinnare.  
Hade webbplatserna varit te.x. olika fotografers webbplatser så hade nog omdömet var ett annat.

När jag surfar runt och jämför olika webbplatser, även sidor utanför detta tests kategori, så upplever jag nog att jag egentligen upplever 4 sekunder som smärtpunkten sett till laddningstid. Ingen av sidorna i detta test klarar egentligen detta men samtidigt så påverkar hur en sida laddar sitt innehåll väldigt mycket, i alla fall i mitt tycke. Att snabbt få en översikt av sidans innehåll och om sidan är "den man söker" spelar större roll än om sidans flashbild har laddats eller inte.


Referenser
-----------------------

###Tryckta  
Beaird, Jason. George, James. (2014). *The principles of Beautiful web design*. 3rd ed. Collingwood: Sitepoint Pty Ltd.

###Webbkällor  
<a href="http://www.leksand.se" target="blank">leksand.se</a> hämtad 2018-12-10  
<a href="http://www.falun.se" target="blank">falun.se</a> hämtad 2018-12-10  
<a href="http://www.borlange.se" target="blank">borlange.se</a> hämtad 2018-12-10  

<a href="https://developers.google.com/speed/pagespeed/insights/" target="blank">PageSpeed Insights</a> hämtad 2018-12-16  

*Genomgång design kmom05 med Emil* (2018).[Video online]. <a href="https://www.youtube.com/watch?v=Cti-Nz2513g" target="blank">https://www.youtube.com/watch?v=Cti-Nz2513g</a> [2018-12-10].

*Föreläsning design kmom05 med Mikael* (2018).[Video online]. <a href="https://www.youtube.com/watch?v=62ZIah6qER0" target="blank">https://www.youtube.com/watch?v=62ZIah6qER0</a> [2018-12-10].


Övrigt
-----------------------

Denna rapport är författad av Johan Hanses och är en del av kmom05 i kursen design vid Blekinge tekniska högskola
