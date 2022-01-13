# Phonebook
Hämta "LearnWeb.html" och kör filen för att testa programmet.

Kodgenomgång
Jag använde mig av Vue.js eftersom jag inte använt mig av något av de tre alternativen tidigare, och jag fick uppfattningen att Vue var enklast att komma igång med.

Json filen hämtas med "XMLHttpRequest", och parsas till an array av object. Objekten sorteras in i vänner och kollegor. v-for används för att skapa en lista med den aktiva telefonboken. "editingIndex" används för att indikera om något och vilket av objekt som redigeras. När index i v-for iteratorn stämmer överens med "editingIndex" göms texten för det objektet och input-rutor visas istället.

html knapparna är kopplade till JavaScript genom v-onclick, som kallar på funktioner. Funktionernas namn beskriver väl vad de utför. I "SaveEdit" används regex för att kolla att texten endast innehåller siffror eller '-'.

Jag skrev lite CSS för att göra det lite finare, men jag hoppas att utseendet inte var fokus för uppgiften 😅
