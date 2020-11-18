# Startfiler för LaTeX

Ladda ner detta repo, genom att klicka på den gröna knappen där det står code
och hämta ner filerna som en zip. Extrahera dessa på lämpligt ställe.

## Installera (Windows)

ladda ner och installera:

* [Miktex](https://miktex.org/download) (Tillåt programmet att ladda ner paket utan att fråga dig)
* [Strawberry Perl](http://strawberryperl.com/)

När detta är installerat öppna TexWorks från startmenyn. Gå in på
Edit->Preferences och klicka sedan på fliken Typesetting. Under rubriken
Processing tools och klicka på plussikonen (+).

Skriv in:
- Name: latexmk
- progam: latexmk

Klicka på plusset ner till höger och lägg till argumentet -pdf (med
minustecknet). Klicka på ok och stäng ner fönstret genom att klicka på ok.
Klicka på menyn bredvid playknappen och välj latexmk. öppna sedan latexfilen
rapport.tex genom File-menyn.

Klicka sedan på playknappen och den borde börja
ladda ner paket och sedan göra en pdf-fil som ska visas upp.

Sedan är det bara att ändra och skriva in grejer efter \begin{document}. Det är
bra att ändra på title, och author så att rätt namn finns med (dessa finns
precis ovanför \begin{document}). Kommandon i LaTeX börjar med ett \, allt annat
är vanlig text som kommer synas. Rader som börjar med % är kommentarer och
kommer inte tolkas som kommandon eller text, där jag lagt till förklarande
text på de flesta kommandon.

Referenserna finns i filen references.bib, där ett exempel ligger.

Det går även att göra pdf-filen utanför texworks, med de två .bat-filerna som
ligger i zip-filen. Dubbelklicka på make_document.bat och den ska göra en pdf.
För att ta bort de filerna som generaras när dokumentet görs kan du klicka på
clean_files.bat.

## Start tutorial på hur man använder LaTeX

[samling med exempel](https://www.latex-tutorial.com/tutorials/)

## Bibliografi-hantering

[En bra samling med exempel och det som finns att göra](https://www.overleaf.com/learn/latex/bibliography_management_with_biblatex)
