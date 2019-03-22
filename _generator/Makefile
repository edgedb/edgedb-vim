.PHONY: fetch-metagrammar regen-grammar


fetch-metagrammar:
	out=$$(edb gen-meta-grammars edgeql) && \
		echo "$$out" > meta.py


regen-grammar:
	PYHTONPATH=$(shell pwd) python gen_grammar.py
