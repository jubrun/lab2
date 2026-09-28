# MIN FÖRSTA WEBBPLATS
Här på den här webbplatsen kan du hitta en kort introduktion om vem jag är och om några av mina intressen.
Det finns även en sida som går lite mer in på hur det är att vara supporter och om hur det är att stötta sitt favoritlag.

## TEKNIKER
För att bygga den här webbplatsen har jag bara använt HTML.
Till den här uppgiften behövdes inte CSS så jag har således inte använt det ännu. 
För att publicera webbplatsen har jag använt mig av Git, GithubPages och Netlify. 

## LÄNKAR TILL PUBLICERINGAR
Här kommer länkarna till mina två publiceringar:

GitHubPages - https://jubrun.github.io/lab2/

Netlify - https://jubrun.netlify.app/

## LITE OM GIT
- Vad är skillnaden mellan git add och git commit?

Genom git add talar man om vilka ändringar man vill ha med, man lägger till ändringarna i 'staging area', som fungerar som ett väntrum. 
Sen när man kör git commit sparas ändringarna som en ny version med historik. I den läggs även tillhörande commit-meddelande.

- Varför använder man branches istället för att jobba direkt i main?

Branches används för att kunna arbeta parallellt med main. Genom att använda branches kan man göra tester och ändringar vid sidan av, utan att det påverkar main. Så man testar och utvecklar separat i olika branches och sen när man är färdig/klar så slår man ihop ändringarna från branchen med main.

- Vad händer rent praktiskt när man gör en merge?

När man gör en merge slår man ihop ändringarna i en branch med en annan branch. Man slår alltså ihop två branches med varandra så ändringarna i den ena förs över till den andra. T.ex. om man gör en merge mellan en branch och main så förs ändringarna i branchen över även till main. 

- Vad är skillnaden mellan att pusha till GitHub och att publicera direkt på t.ex. Netlify?

Att pusha till Github innebär att man skickar sin kod från det lokala t.ex. sin dator till ett remote repository, där lagras/versionshanteras det man sparat i en form av molntjänst. Det kan vara för en själv, för kollegor m.fl. Men om man inte publicerar vidare via t.ex. GitHubPages så är projektet ännu inte tillgängligt för fler än de som har åtkomst till GitHub-repot. 
Medan Netlify är en publiceringtjänst/webbhotell som publicerar webbplatsen och gör den tillgänglig för alla via en webbadress på internet. 

- Om du vill exkludera någon fil i projektet från versionshanteringen, hur gör du då?

Då skapar man en fil i rotmappen som man döper till .gitignore. I den skriver man sedan in vilken/vilka filer som ska undantas från versionshanteringen. 
