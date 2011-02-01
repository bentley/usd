ROFF ?= troff
POST ?= grops

all: ref.ps

ref.ps: ref.ps
	${ROFF} -me $> | ${POST} > $@
