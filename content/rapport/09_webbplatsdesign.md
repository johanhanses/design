Analys av webbplatsdesign och aktuella trender
=======================



Urval
-----------------------

Jag har valt följande tre webbplatser att analysera utifrån aktuell webbplatsdesign
>    <a href="https://www2.hm.com/sv_se/" target="blank">hm.se</a>
>
>    <a href="https://www.kappahl.se" target="blank">kappahl.se</a>
>
>    <a href="https://www.ahlens.se/" target="blank">ahlens.se</a>


Alla tre webbplatserna är klädbutikskedjor och bedriver e-handel såväl som i butik. Gemensamt är att alla säljer kläder till den "breda massan" och just dessa har valts ut i en kombination av "på måfå" och att det är fysiska butiker som jag känner till och vet att de även har e-handel.  


Metod
-----------------------

De aspekter jag kommer att titta på för varje webbplats är:

> -Mobilanpassning/responsivitet, hur fungerar sidan att använda vid olika skärmstorlekar?  
> -Navigering, är det lätt att finna det man söker?  
> -Kort om layouten, vilka regioner finns med?  

Jag har besökt webbplatserna från på min macbook pro med 13-tums skärm i webbläsaren firefox developers edition samt från min iphone 8. Samtliga webbplatser är besökta från och med 20190111 till och med 20190116.

Resultat
-----------------------

###hm.se
[FIGURE src="image/hm.png?w=600" class="center" caption="H&Ms webbplats för e-handel, hm.se" alt="hm.se"]

hm.se beter sig hyfsat när jag minskar webbläsarens fönsterstorlek. Problem uppstår främst i navbaren men även headern som i hm.ses fall består av länkar av den typen man oftast finner i en footer beter sig inte heller optimalt vid skärmstorlek motsvarande mobiltelefoner. länkarna staplas på varandra och en sökfunktion som vid desktopskärmstorlek ligger till höger om navigationen blir vid ståendemobilt läge intryckt i nederdelen av navigationens länkar.  
Vid ett besök på webbplatsen i min iphone så funkar dock sidan utmärkt. Delar som tidigare staplades på ett mindre snyggt sätt ser nu bra ut och navigationen och övrigt innehåll skalar nu betydligt bättre. Vid en titt på sidans källkod så finner jag ett skript som känner av vilken enhet besökaren använder sig av för att visa sidan. Scriptet laddar en stilmall för desktop oavsett vilken storlek jag gör webbläsaren till.

Navigationen är placerad högst upp på startsidan och ligger kvar högst upp på samtliga sidor som navbaren länkar till. För man musen över en kategori så kommer en drop down-meny med alla underkategorier. Väljer man inte någon underkategori så presenteras underkategorierna i en ny region till vänster för varje ny undersida.

Layouten är enkel och tydlig, header med länkar och navbar. En main-sida med innehållet för sidan och dess undersidor. På maindelen finns det ibland ytterligare navigering för att nå valt kategoris undersidor. Sidan avslutas med en footer med sedvanliga länkar.

###kappahl.se
[FIGURE src="image/kappahl.png?w=600" class="center" caption="Kappahls webbplats för e-handel, kappahl.se" alt="kappahl.se"]

kappahl.se upplevs som helt responsiv vid mindre olika fönsterstorlekar i webbläsaren. Headern och dess innehåll i form av navigation och övriga länkar anpassar sig till skärmstorleken och ändrar utseende därefter.
Vidare så ser jag tre olika bildstorlekar på deras produkter när jag minskar skärmen steglöst. Med detta menat att det är art direction på bilderna och att det ligger tre olika bildstorlekar i varje <picture> element.

Navigationen är placerad högst upp på startsidan och hänger med genom alla sidor som presenteras i navbarnen.
För man musen över en kategori så får man en drop down-meny med alla underkategorier. Väljer man inte någon underkategori så har varje kategori en egen startsida och man får via navbarens drop down-meny gå in till sina underkategorier. Navbaren ligger på kappahl.ses webbplats kvar högst upp i fönstret även när besökaren scrollar ner på sidan.

Layouten är enkel och tydlig, header med länkar och navbar. En main-sida med innehållet för sidan och dess undersidor. På maindelen finns det ibland ytterligare navigering för att nå valt kategoris undersidor. Sidan avslutas med en footer med diverse länkar.

###ahlens.se
[FIGURE src="image/ahlens.png?w=600" class="center" caption="Åhlens webbplats för e-handel, ahlens.se" alt="ahlens.se"]

ahlens.se webbplats fungerar bra och responsivt i webbläsarens olika fönsterstorlekar. Header med länkar och navbar anpassar sig väl efter olika skärmstorlekar och vid minsta läget i datorns webbläsare liknande det från mobilt besökande så ser sidan i princip likadan ut som på mobilen. Innehållet, främst bilder är art directade och skalar och byter ursprungsstorlek beroende på fönsterstorlek.

Navigeringen/navbaren är placerad högst upp på sidan i dess headerdel. När man scrollar ner på sidan så ligger navbaren kvar och nås därför var du än är på sidan. För man musen över navbarens länkar/kategorier så får man en drop down-meny med underkategorier. Klickar man inte på en underkategori utan bara på "huvudlänken" i navbarnen så kommer underkategorierna som ytterligare länkar/navigation till vänster om sidans main-innehåll.

Layouten är enkel och tydlig, header med länkar och navbar. En main-sida med innehållet för sidan och dess undersidor. På maindelen finns det ibland ytterligare navigering för att nå valt kategoris undersidor. Sidan avslutas med en färgrann footer med olika länkar.


Analys
-----------------------

Uppgiften var att se aktuella trender för webbplatsdesign och jag har tittat på klädbutikskedjors webbplatser för e-handel. Webbplatserna har främst studerats utifrån responsivitet och hur lätt man som besökare finner det man söker.

Personligen finner jag det tråkigt att de olika webbplatserna är så otroligt lika varandra sett till undersökta parametrar men även i stort så ser det mesta likadant ut. hm.se har en annan lösning på sin responsivitet än de två andra webbplatserna men resultatet är dock en mobilanpassad webbplats.

Navigationen och drop down-menyerna fungerar på liknande sätt på alla tre webbplatserna, vad som främst skiljer dessa tre webbplatser åt är att hm.se inte väljer att låsa sin navbar högst upp på sidan oavsett var man som besökare är och bläddrar på sidan.

Sidorna gör det dom ska och anpassar sig till din, som besökares, enhet. Du bör inte ha några större problem att köpa ett par byxor så länge du vet vilken storlek du ska ha.

Referenser
-----------------------

###Tryckta  
Beaird, Jason. George, James. (2014). *The principles of Beautiful web design*. 3rd ed. Collingwood: Sitepoint Pty Ltd.

Övrigt
-----------------------

Denna rapport är författad av Johan Hanses och är en del av kmom07/10 i kursen design vid Blekinge tekniska högskola
