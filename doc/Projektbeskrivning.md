# Kampanjsite för konsumentprodukten Mr. Foot
Projektmedlemmar: 
[hg222dt](https://github.com/hg222dt)

[Exekverbar version av projektet ](https://c9.io/hg222dt/projekt_site_131027/workspace/index.html)
[Länk till projektet på Cloud 9](http://c9.io/hg222dt/projekt_1ik415)

## Beskrivning av projektet
Syftet kommer vara att skapa en site för att lansera och sälja en konsumentprodukt. Siten ska fungera som en kampanj-site, med funktionalitet för kunna beställa produkten. Kundens beställning kommer att kunna göras via siten, men i grunden är det en annan underleverantör som direkt tar emot alla uppgifter kring respektive order, och sköter allting därefter.

Siten kommer att byggas upp med hänseende på tre olika aspekter.

1. Lansering. Förutsättningar ska ges för att användare enkelt kan ta in de främsta budskap som produkten och dess försäljning kretsar kring.

2. Interaktion. Användare som är lite mer intresserade (eller har blivit det efter den förra aspekten) ska kunna dyka aningen djupare in i sitens universum, genom att kunna bistå till ett fotoalbum, där man ska ha möjlighet att ladda upp en bild på hur man använder eller tänker sig kunna använda produkten som säljs. Man ska även kunna skriva en kommentar till en bild.

3. Försäljning. Produkten ska säljas från siten, via ett enkelt formulär som användaren får fylla i. Detta ska förmedla en sömlös känsla av enkel- och säkerhet.


## Tekniker
Detta kommer i grunden att skapas med hjälp utav HTML5 och CSS3.



###HTML

####Video-taggar
Video-taggar kommer att användas i syfte ge bloggen video-funktionalitet, samt att ge lanseringen av produkten en extra krydda av rörlig bild.


####HTML 5-taggar för bättre semantik och sökbarhet
För att göra sidan så pass sökbar som möjligt ska vi tagga upp alla element i HTML 5-anda, med taggar som <main>, <header>, <content>, <nav>, <aside> mm.


####Formulär
För att kunna sälja produkten, kommer vi att inrätta ett enkelt formulär på siten, där man matar in uppgifter inklisive betalningsuppgifter. I denna demo-verison av siten kommer dock en exempel-användare att låtsas ha betalat när användaren matat in sina uppgifter.


####Placeholder
I vår formulär tänker vi anända oss av placeholder-egenskapen, för att ge en skönare upplevelse i formuläret som ska fyllas i.


####Email-input kontroll
I formuläret ska även den inmatade e-postadressen valideras med hjälp utav HTML som ser om en giltigt formaterad e-postadress har matats in.


####En nyhetssida/blogg
En central pelare på siten, är en blogg som matar besökaren med nyheter kring produkten. 


####Externa typsnitt
I form av api:er från google fonts, komemr vi även att imortera externa typsnitt till vår site.


###CSS
Två stycken stillmallsdokument kommer att skapas. Ett kommer användas till mobila enheter (dvs enheter med mindra skärmbredd) samt ett annat kommer att användas till normala skärmstorlekar på datorer.

####SASS
Användning av CSS-extention SASS kommer troligtvis att ske. Främst i syfte att lära sig mer om det.

####Animationer
Vi kommer att försöka skapa en skön, mjuk upplevelse och kommer därför att använda oss av ett par animationer. Dels i menyn till navigeringen av siten och dels i syfte att skapa ett slags fotoalbum, med en mjuk användarupplevelse.
I detta fotoalbum kommer även en funktion i att som användare ladda upp bilder till siten, från sin mobila enhet eller dator. 



## Begränsningar
Vi kommer inte att bygga ut den interaktiva delen, mer än att det går att ladda upp bilder gemensamt till ett fotoalbum, och att en kommentar kan läggas till varje bild. Detta på grund av begränsning i tid.

## Tidsplanering

Tryck [här](https://docs.google.com/spreadsheet/ccc?key=0AmeqMJ4YRHYOdEtRTFFCcEN0R1lSX0s4MTc4M0JKa1E&usp=sharing) för att komma till tidsplaneringen.

