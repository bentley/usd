ROFF ?= troff
POST ?= grops

all: learn.ps

learn.ps: learn.ms
	${ROFF} -ms < $> | ${POST} > $@
