ROFF ?= troff
POST ?= grops

all: msdiffs.ps

msdiffs.ps: ms.diffs
	${ROFF} -ms < $> | ${POST} > $@
