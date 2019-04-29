# uvod

#### Ahoj holky/dámy,

tady najdete instrukce v třech krocích, co a jak nainstalovat, abychom mohly pokračovat se C# v Githubu.

# instalace

#### 1. Otevření Github účtu
Přejdete na stránku www.github.com a tam vpravo na hoře klikněte na “Sign Up”. Vyplňte všechny požadované polička: user id nemusí být vaše opravdové jméno a příjmení, ale kdybyste (nahodou) uvažovaly o tom, že své repozitoria někomu v budoucnu ukažete (např. budoucímu zaměstnavateli), tak zvažte tady nějaký vhodný nazev :-)

Pak na obrazovce “Choose your subscription” volime opci “zdarma” a rovnou klikame  “Continue”. Na následující obrazovce už je to na vás kolik toho o sobě sdělite na Githubu.  Generalně, necháme se vést až k vytvoření účtu.

Github bude vám rovnou nabizet abyste utvoříly nějaké první repozytorium “hello world” - je to na vás, můžete - nemusíte. Podstatné je, abyste ověřili vytvoření účtu v mailu, který vám Github pošle.

#### 2. Instalace rozšíření Github pro Visual Studio

Otevřete Visual Studio. Tam v Menu Tools klikněme ‘Extensions and Updates’:  
![](/01.png)

Měly bychom vidět tuhle obrazovku. Klikáme “Online” a následně  “Download” Github Extension for Visual Studio.
![](/02.png)

Nechame se vest instalačním wizardem až uvidíme konečně okno, že máme hotovo.
![](/03.png)

Ted musite udělat něco, co je těžce vysvětlit: zavřete Visual Studio.

Nasledně otevřete Visual Studio a na Menu View klikněte na “Team Explorer”, měly byste vidět tohle. Klikame “Connect”
![](/04.png)

Objeví se logovací okno do Github. Logujeme se na svůj účet.
![](/05.png)

To ale nemůže ještě plně fungovat jelikož chybí nám Git. Vpravo v Team Exploreru klikame na ikonu “domečku”. 

Následně “Settings”:

![](/06.png)

Zase: nechame se vest instalačním wizardem až uvidíme konečně okno, že máme naistalovaného Gita. 
![](/07.png)
 
Pak v Team Exploreru v Manage Connection zkusíme se připojit na Github. Pokud se podaří, můžete si zkusit vytvořit nějaké repositorium a to takhle, že libovolný projekt v C# odešlete na svůj účet v Githubu.

![](/09.png)

# obsluha 

Zamíříme se ted na publikování svého kódu na Github - jenom to, nic víc. Čili o cestu z “našeho počítače” na Github. Zkratka, mame program(y) a chceme ho(je) publikovat/poslat na Github. Tohle lze udělat v dvou “logických” krocích: za prvé, musime nahrát náš kod na tzv. “lokální repositorium” a za druhe, z lokálního repositorium nahrajeme na Github.
Takže, otevřeme si projekt/solution, který chceme publikovat. Ve “File” klikněme “Add to Source Control”

![](/VS01.png)

Jenom pro kontrolu podivame se do Team Explorera v Manage Connections (ikonka vpravo od “domečku”), zda se nám objeví na seznamu náš projekt. To je jenom kontrole, je možne ten krok přeskočit.


![](/VS02.png)

Jelikož cpu všechny programy z kurzu do stejného repositorium na Github, tak kvůli pořádku publikuju jenom jeden projekt v jedné větvi (v jedné branch). Je možné to dělat jinak: jeden projekt = jedno repositorium. Ale asi se shodneme, že cvičné programy nejsou moc reprezentativní, tak ja je cpu do jednoho repositorium - je to ale na vás, postup je stejný = akorát když chcete pro každý projekt mít jedno repositorium, tak ten krok můžete přeskočit. Tady si totéž definujeme nový branch (pro nový projekt v ramci stejného repositoria). Přejdeme do Branches, klikněte New Branch, napište název te nové větvi a potvrdite Create Branch:

![](/VS03.png)

Mělo by to vypadat takhle - na obrazku nová větev se jmenuje Test08, větev master je tam vždycky!!!

![](/VS04.png)

Nasledne přejdeme do Sync

![](/VS05.png)

Klikněme Publish Git Repo v Push to Remote Repository:

![](/VS06.png)

Chce to po nás nazev našeho repositorium na Github, jako tady na tom obrazku:

![](/VS07.png)

Vklejime tam url adresu našého Github repositoria a klikněme Publish:

![](/VS08.png)

Hotovo! Měly byste vidět své dílo na Github. Např. jako na obrázku níže:

![](/VS11.png)

Po rozkliknutí větví můžete si najít požadovanou větev:

![](/VS12.png)


#### Pro Martinu (a vsechny ostatni :-))

Ve Visual Studiu v Team Exploresu nastavis Settings

![](/2019-04-27.png)

Klikneme v Repository Settings

![](/VS2.png)

A najdeme Remotes, ja tady na svym pc mam uz nastaveno dve repozitory: jedno je moje, druhe je "nase" - skupinove, ty nejspis nemas tam nic - nevadi, za chvili si to nastavis

![](/VS3.png)

Klikneme "Add"

![](/VS4.png)

Mela bys uvidet neco takoveho

![](/VS5.png)

Vyplnis to adresou sveho Githuboveho uctu - tam kde budes "nahravat" sve kody (placla jsem tam jedyne repozitorium, jake jsem nasla na tb=vem Github uctu, ale muzes to zmenit, dala jsem to jen tak pro priklad). Samozrejme muzes si pridat i ten skupinovy adresar, kdybys chtela publikovat sve reseni - vrele doporucju a vubec: holky, delte se kodem, je to jen zabava C# a githubem (zatim :-) casem muzeme dokonat velke veci!!!).  

![](/VS6.png)

#### 3. Přidání “kolaborantů” :-)
Sdělte mi na fb své Github usery a já vás přidávám do našeho společného projektu “C#  Coding Club” (cscc).
