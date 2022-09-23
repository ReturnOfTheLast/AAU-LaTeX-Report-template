# AAU-LateX-Report-template
En omstrukturering af AAUs officielle LaTeX-skabelon, med fokus på brugervenlighed, overskuelighed, strømlining og især at nye brugere af LaTeX ikke overvældes af alle mulige filer som ikke bruges af selve PDF-rapporten.
Original/official template = https://github.com/jkjaer/aauLatexTemplates

Instructions:
1. Vælg om du vil have en forside med billede eller uden billede:
Dette vælges under setup/1-documentSetup.tex med variablen \def\myForsideMedBillede{} i linje 5
\def\myForsideMedBillede[0] = Forside uden billede
\def\myForsideMedBillede[1] = Forside med billede

2. Udfyld alle felterne i filen for at fylde forside, colophon, titlepages og preface

3. Udfyld Abstract(resumé) på dansk og engelsk i filen setup/2-documentAbstracts.tex

4. Skriv dokumentet. (:

Hjælp til formatering/kommandoer kan findes i media-mappen:
Guide / Cheatsheet udarbejdet af IDA: media/IDA LaTeX Cheatsheet.pdf