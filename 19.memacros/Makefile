ROFF ?= troff
POST ?= grops

all: intro.ps

intro.ps: intro.me
	${ROFF} -me $> | ${POST} > $@
