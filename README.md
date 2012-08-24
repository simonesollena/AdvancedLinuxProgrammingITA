Programmazione avanzata su linux
=================================

Traduzione italiana dell'opera ADVANCED LINUX PROGRAMMING
---------------------------------------------------------

Original book online:
[Advanced Linux Programming](http://www.advancedlinuxprogramming.com/)

Sono presenti i sorgenti in LaTeX ed il file pdf ottenuto dalla compilazione dei sorgenti: alp.pdf
Per la generazione del pdf è stato utilizzato il comando
`pdflatex alp.tex`

In caso di problemi nel riconoscimento dei caratteri nel sorgente LaTeX provare a visualizzare i documenti impostando nel proprio editor la codifica ISO-8859-1 o Windows-1252.

____________________

Sintassi caratteri e comandi utilizzati:

virgolette aperte e chiuse:

	`` e ''

Listati da file:

	\listfromfile{nomefile visualizzato}{descrizione}{riferimento list:X.Y}
		{percorso/nomefile}

Codice in C:
	\begin{listcodeC}
		codice codice codice
	\end{listcodeC}

Codice in Basch

	\begin{listcodeBash}
		codice
	\end{listcodeBash}

riferimenti a capitoli/sezioni/sottosezioni, con titolo:

	\numnameref{subsec:x.y.z}

note a margine:

(attualmente utilizzate per riferimenti a capitoli o sezioni non ancora presenti,
da rimuovere in futuro)

	\marginpar{nota}

nota a piè di pagina:

	\footnote{nota}

citazioni di testo con relativo titolo:

	\begin{quote}
		{\large\textbf{Titolo}}\\
		testo citato
	\end{quote}
