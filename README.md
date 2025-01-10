# LaTeX-Unterlagen

> "In diesem Repository befinden sich die LaTeX-Unterlagen zum Modul."

---

## Inhalt

Der Inhalt entspricht dem Text der **Aufgabe 2** des Moduls.  
Es kann sinnvoll sein, sich die PDF zur Aufgabe 2 noch einmal anzusehen.

---

## PDF erstellen

Das geht ganz schnell und einfach:

1. **LaTeX installieren:**  
   [tug.org/texlive](https://tug.org/texlive/)  
   
2. **PDF erstellen:**  
   - Mit `PDFLaTeX`:  
     ```bash
     pdflatex ./task.tex
     ```  
     *(Dieser Befehl muss mehrfach ausgeführt werden, damit die PDF vollständig generiert wird.)*  
   - Alternativ mit `LaTeX Mk`:  
     ```bash
     latexmk -pdf ./task.tex
     ```

---

## ⚠️ !!Achtung!!

LaTeX erstellt einige nervige Dateien (`.aux`, `.log`).  
Diese **muss man löschen**, bevor man einen Commit mit seinen Änderungen macht!