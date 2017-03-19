all: 
	@pdflatex -halt-on-error -shell-escape core_notes.tex
	@makeindex core_notes.idx

clean:
	@find -name ".*~" -delete 2>/dev/null
	@find -name "*~" -delete 2>/dev/null
	@find -name "*.aux" -delete 2>/dev/null
	@find -name "*.bbl" -delete 2>/dev/null
	@find -name "*.idx" -delete 2>/dev/null
	@find -name "*.ilg" -delete 2>/dev/null
	@find -name "*.ind" -delete 2>/dev/null
	@find -name "*.lof" -delete 2>/dev/null
	@find -name "*.log" -delete 2>/dev/null
	@find -name "*.lot" -delete 2>/dev/null
	@find -name "*.out" -delete 2>/dev/null
	@find -name "*.pdf" -delete 2>/dev/null
	@find -name "*.toc" -delete 2>/dev/null
	@echo "Cleaned"
