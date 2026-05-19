# Vad datasetet är
Nasa Near-Earth Asteroids 
Detta är ett dataset som innehåller data om asteroider som krettsar nära jorden i vårat solsystem.
Mer specifikt handlar det om asteroider i grupperna Amor, Apollo och Aten, vilka är olika typer av banor runt solen.
Dessa asteroider passerar nära jorden, två av grupperna har banor som korsar jordens bana runt solen.


# Var datan kommer ifrån 
Denna datan är hämtad från Kaggle där informationen ursprungligen kommer från NASA's öppna API NeoWs



# Notebook 
notebooken körs i så mycket ordning jag kunde få till! 
Det börjar med att importera alla paket som jag använder mig av. 
Sedan börjar jag med att testa runt och kollar på vad datan är lite lätt sen börjar jag med simpla grafer för att se lite mer visuellt på datan. 

Jag använder mig av pandas för att läsa in csv filen och sedan matplot för att plota ut datan. 
Anser att detta är ett simpelt sätt att göra det på och ville inte komplicera det för mycket.

Jag gör även en data tvätt med hjälp av dropna för att droppa dem rader som har NaN-värden

Dem flästa grafer jag har är stapel grafer och det är för jag upplever att det är lättast att visa. 
Önska jag kunde visa mer data på andra sätt. 


# Slutsatts 
En tydlig slutsats från den data jag fick fram var vilken bana som hade flest farliga asteroider.
När man tittar på hur dessa banor ser ut ser man tydligt varför det är så.

Det man också tydligt kan se är sambandet mellan magnitud och asteroidernas diameter.
Ju större asteroid, desto lägre ljusstyrka.



struktur 
så simpelt som möjligt förklara analytiskt. 