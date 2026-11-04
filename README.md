# Dating-dossieret

En enkel, frittstående nettside for å holde oversikt over dating-livet: hvem du tar med videre, privat vurdering, og en «tea»-visning med avstemning for venninnene.

- Én fil: `index.html` (ingen build, ingen avhengigheter, ingen server).
- All data lagres **kun i brukerens egen nettleser** (localStorage). Ingenting sendes noe sted.
- «Sikkerhetskopi» og «Last inn» eksporterer og importerer data som en JSON-fil.
- Avstemning skjer på samme enhet via «Vennevisning».

## Kjøre lokalt

Dobbeltklikk `index.html`, eller kjør `python -m http.server` i mappen og åpne http://localhost:8000.

## Personvern

Ikke legg inn ekte data i repoet. `.gitignore` ekskluderer JSON-filer slik at sikkerhetskopier ikke havner her ved et uhell.

## Deployment

Siden er ren statisk HTML og kan legges på hvilken som helst statisk hosting. I organisasjonen håndteres deployment via infra-teamet.
